# Discussion and Reference

## Table of content

6.1. [Options for Optimization](#61-options-for-optimization)

6.2. [Example Instruments for System Guidance Panel](#62-example-instruments-for-system-guidance-panel)

6.3. [Math Reference](#63-math-reference)

6.4. [Other References](#64-other-references)

## 6.1. Options for Optimization

**These Options Are Not Necessary, but May be Advantageous.**

They have the disadvantage of making it more difficult for people to understand the voting math.

* account snapshotting combined with exponential-curve and power law analysis and timing allows emphasizing accounts that are relatively certain to not be misrepresenting themselves

* Use of zero knowledge proofs in order to allow ZPIVs to influence voting.

* allowing exchanges to vote in the network effect layer

* creation of defense and defense intelligence functions to play a role in network support and intelligence layers. Such defense function may be responsible for legal and memetics concerns (Public Relations).

* use of automatic network tuning mathematics to auto-tune the voting/feedback system.

* use of private identity systems to bolster voting information

* Use of transaction fee information to bolster voting information

* use of iterative voting

* use of vote history to adjust vote weights


## 6.2 Example Instruments for System Guidance Panel

Some of these measures have already been implemented.
See:  http://www.presstab.pw/phpexplorer/PIVX/index.php,  http://pivx.masternodes.pro/

* least squares approximation of negative exponential curve distribution for account values below 10k pivs
* least squares approximation of power law curve distribution for account values above 10k pivs
* Pivs in Masternodes vs Pivs Staked
* Number of Masternodes
* Number of Staking nodes
* Transaction volume/day
* Layer vs layer vote percentages
* Vote blocking events where a single layer blocks below the blocking threshold
* Number of Vote Nodes
* Average PIVS represented by vote nodes
* Average number of accounts represented by vote nodes
* BTC and USD prices
* rms price volatility measure
* BTC/USD price derivatives
* Estimated price shift time constant (amount of time required to make 63% of a price correction)
* Estimated current value (based primarily off of a single pole fir filter with above time constant)
* Estimated pump pool size
* Estimated dump pool size


## 6.3. Math Reference

The network calculation used to determine a decision based on the individuals votes will take the general form of a 4 layered feed-forward network with the first three layers being non-thresholding layers while the fourth implements a complex system of interrelated thresholds. These four network math layers are not to be confused with the lay-person voting layers. They are calculation machinery, and not human-subjective function description. The input data will take the form of vectors of ternary numbers (+/0/-).

The first network layer will be the input data.  The first set of weights is derived from chain data, and will weigh the input data into nodes of the second network layer which represents a detailed list of currency related functionalities. The form of the data at this point will be vectors of integers. They will be accompanied by additional scalars, which retain the number of original non-zero votes for each function. The scalars may be used to determine vote percentages. Those functionalities, once summed, will be weighed into the third network layer.

The third network layer will contain a list of the primary value dimensions (or lay-person voting layers). The data in that layer will be summed according to the weight scheme chosen for the three value dimensions. It consists of vectors of integers and scalars

The fourth network layer sums data from the vectors of integers and scalars from the third layer into a mutually suppressive thresholding system. The vector data is split from vectors into scalars. Each node of the fourth layer represents one of the elements of the vectors.  Each node of the fourth layer fills a thresholding function and outputs a single boolean number, all, except for one of which being 0 (not chosen)  while one of which is 1 (chosen).


## 6.4 Other References

https://en.wikipedia.org/wiki/Electoral_system <br />
https://en.wikipedia.org/wiki/Social_choice_theory  <br />
https://en.wikipedia.org/wiki/Arrow%27s_impossibility_theorem <br />
https://en.wikipedia.org/wiki/Gibbard%E2%80%93Satterthwaite_theorem <br />
https://en.wikipedia.org/wiki/Cardinal_voting <br />
https://en.wikipedia.org/wiki/Condorcet_paradox <br />
http://www.cds.caltech.edu/%7Emurray/books/AM05/pdf/am06-complete_16Sep06.pdf <br />


Contributors:
The information and ideas required to build this document come from a large number of individuals. <br />
Turtleflax, Openbaringen, Nitya, Presstab, Alexanderluthor, cryptosi, Grant, derek_hansen, Trismegistus, mgshightech
