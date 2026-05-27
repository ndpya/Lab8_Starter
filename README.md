# Lab8-Starter


*How are graceful degradation and service workers related?*

Graceful degradation is the concept where a system is still able to function in a reduced state or when top level features fail as opposed to failing silently or crashing. Similarly, service workers serve as a fallback for when users lose internet connectivity. At the event a user is offline, the service worker is able to intercept network requests and serve cached resources and assets as a fallback instead of breaking completely, allowing users to still be able to use the website. 