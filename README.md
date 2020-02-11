# Adventure 2.5

This is the C source code (plus Makefile) downloaded from [ifarchive.org](http://www.ifarchive.org/if-archive/games/source/Adventure2.5.tar.gz) with a minimal set of changes such that it compiles without warnings and runs on 2020 era machines. See the commit log for details.

The [ieure/Adventure2.5](https://github.com/ieure/Adventure2.5) project is a similar effort and the work here has been cross-checked against Ian's. However, the *ieure* project has not been touched since 2009 and the code did not compile cleanly for me in 2020. Furthermore, the *ieure* code is a bit more than minimal changes.  But thanks!

## testing

The code compiles cleanly via the Makefile on Darwin and Linux (Docker offical iamge: gcc:9.2.0) 
Note that only the simplest "smoke test" for runtime behaviour has been done!
