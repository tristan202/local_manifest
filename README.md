local_manifest
==============

My own simple modifications to AOKP. All credits to them.
This local_manifest.xml file replaces packages/apps/Mms
with the one from the CM10 repo, which has quick reply built
in. It also replaces frameworks/base, as I wanted a centered
lockscreen. It is not an option like in CM, it is hardcoded
into the xml. Lastly it contains danish translation for
packages/apps/ROMControl.

All you need to do is clone into the git, and place
local_manifest.xml inside <your_AOKP_source>/.repo, and
do a repo sync.