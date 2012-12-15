panopticon
==========

Hub for monitoring and messaging systems to guide household security systems.


When a camera sytem like zoneminder is used for household security, the system
typically needs to distinguish permitted events from nonpermitted events, or
else the residents of the house will always be triggering alerts.  This
project intends to tie together a messaging bus, to accept status inputs,
with a monitoring system (initally zoneminder), and finally to send alerts.
