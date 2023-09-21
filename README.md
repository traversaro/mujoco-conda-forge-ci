# mujoco-conda-forge-ci

Unofficial continuous integration for [MuJoCo](https://mujoco.org/) compiled against [conda-forge](https://conda-forge.org/)-provided dependendecies. 
The goals of this CI are:
* Ensure that the options present in MuJoCo that permit to build against system dependencies work as intended even in the HEAD version of MuJoCo, as those options are not tested in the official MuJoCo CI.
* Ensure that changes in libraries present in conda-forge do not create regressions in MuJoCo test suite.

