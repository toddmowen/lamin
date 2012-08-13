lamin - Lambda Miner
====================

 * browsergame, written in javascript
 * based on the task for the ICFP(International Conference on Functional Programming) Programming Contest 2012
   * http://icfpcontest2012.wordpress.com/
   * http://www.icfpconference.org/

Map sources are in the assets/maps directory.


Build instructions
------------------

If you cloned this repo without `--recursive`, you need to run:

    git submodule init
    git submodule update

To build, make sure you have NodeJS in your path, and run:

    tools/minify.sh
