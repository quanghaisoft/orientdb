# orientdb
I have spent nearly 1 year successfully applying orientdb to commercial web projects of a large corporation in Vietnam.
The cluster of 6 nodes has encountered many errors from the client to the server, most of which are due to poorly configured configuration, servers that fail to sync, and data disputes, In order to successfully apply graph orientdb, you must have a data synchronization model, tables that are not updated by threads of different processes, and many other things.

 
  
I had to build 2 cluster clusters with 6 servers each to backup each other so that one cluster would die and then rebuild the cluster and the other still ran because I didn't fully trust this new system.
The fastest way to rebuild the cluster is to turn it off and get to a master server and copy it to other servers
