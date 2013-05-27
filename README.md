Instamo
=======

Introduction
-----------

Instamo makes it easy to write some code and run it against a local, transient
[Accumulo](http://accumulo.apache.org) 1.5 instance in minutes.  No setup or
installation is required.  This is possible if Java, Git, and Ant are already
installed by following the steps below.

```
git clone git://github.com/mobileAgent/instamo-ivy.git
cd instamo-ivy
emacs src/main/java/instamo/AccumuloApp.java
ant -Dclass=instamo.AccumuloApp run
```

Map Reduce
----------

Its possible to run local map reduce jobs against the MiniAccumuloCluster instance.   There is an example of this in the source.  The following command will run the map reduce example.

```
ant -Dclass=instamo.MapReduceExample run
```

Purpose
-------

This project proves that I don't need maven to get work done.

Comparison to Instamo
--------------------------

This is a Mock KeithTurner project. It will never be as fast
or as reliable as the real KeithTurner. It only exists to spit on maven.
See the real work in http://github.com/keith-turner/instamo

