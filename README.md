# room-database
---
![Room persistance library](https://i1.wp.com/blog.mallow-tech.com/wp-content/uploads/2018/04/imagem_blog-e1512640321599.png?fit=630%2C335 "Room persistance library")
---
Room provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite.
Apps that handle non-trivial amounts of structured data can benefit greatly from persisting that data locally. The most common use case is to cache relevant pieces of data. That way, when the device cannot access the network, the user can still browse that content while they are offline. Any user-initiated content changes are then synced to the server after the device is back online.

![Room architecture diagram](https://developer.android.com/images/training/data-storage/room_architecture.png?authuser=1 "Room architecture diagram")
