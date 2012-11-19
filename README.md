local_manifest
==============


local manifest for CM9 / CM10 for replacing CM repo's for Jellaxy specific



Little How-To
=============



Repo init CM as described in their howto.

Outside Android source tree, do

https://github.com/Jellaxy/local_manifest.git
cd local_manifest
git checkout ics
cp local_manifest.xml /path/to/your/android/sourcetree/.repo
cd /path/to/your/android/sourcetree/
repo sync -j16

compile android like you use to do.

Have fun!

