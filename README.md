# tailfail

For certain long-running or verbose commands, you want to:

 - see very little information when the command succeeds
 - see more information when the command fails
 - output a progress indicator (especially handy for tools which
   assume a command is stuck if it doesn't print something
   for an extended period of time)


This command acts a bit like `tail`, except only on failure, and with
optional progress indicator (in either seconds or lines).

## Installation

Copy `tailfail` somewhere and run it, you just need python.
