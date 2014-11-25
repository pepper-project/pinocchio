# pinocchio #

Our independent Pinocchio implementation is integrated with the [latest code](https://github.com/pepper-project/pepper/) and with [prior releases](https://github.com/pepper-project/releases/) since Zaatar.

(Specifically: Zaatar, Pantry, and Buffet all contain this implementation.)

To enable the Pinocchio backend, `#define PROTOCOL PINOCCHIO_ZK` in `pepper/common/utility.h`.

The Pinocchio backend is based upon

Parno, B., Gentry, C., Howell, J., and Raykova, M. "[Pinocchio: Nearly practical verifiable computation.](http://research.microsoft.com/apps/pubs/default.aspx?id=180286)" Proc. IEEE S&amp;P, 2013. ePrint also available: https://eprint.iacr.org/2013/279
