# service worker recommendations from Alexander Pope
 
- use async await
- register the service worker in load event
- use waitUntil for cache files
- use a version for the cache
- avoid forcing activation with **skipWaiting()** 
- never rename the service worker file
- set the correct cache headers to the service worker file
  ```
    cache-control: max-age=0,no-cache,no-store,must-revalidate
  ```
- add a  feature flag for control the    unregistration of the  service worker
- don't cache bad responses from fetch api
- don't store global variables
- test your service worker




