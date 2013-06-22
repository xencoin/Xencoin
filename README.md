Xencoin - a fork of Litecoin version with fast block time and faster confirmations (6 confirmations needed). Like Litecoin it uses scrypt as a proof of work scheme.

	- 20 seconds block target
	- Difficulty retargets every 0.40 day
	- Total coins will be around 2100 millions. 
	- Each block will have 200 coins per block at the beginning, it will be halved every two years (or 3,11,400 blocks).
	- The default ports are 4334(connect) and 4335(json rpc).


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
