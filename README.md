# dmubook-errata
Errata to Decision Making Under Uncertainty: Theory and Application

These items have been fixed in the second printing and later.

* Alg. 4.12 (line 4): replace ; with | to be consistent with the notation used in this section (Jon Cox)
* Eq. 6.11: switch a and s in the transition function to be consistent with the notation in the book (Max Egorov)
* Eq. 2.61: (v_i - \hat\mu) should be squared
* P. 59, sentence before eq. 3.3: replace u^1 with c^1 (David Wagner)
* Sec. 3.1.1: in independence condition, second \succ should be \succeq (Ellen Blaine)
* Fig. 3.6: The code used to generate this figure had a small bug. The histograms should be more distributed as shown [here](http://nbviewer.jupyter.org/github/sisl/aa228-notebook/blob/master/07-Games.ipynb).
* Sec. 4.2.4 (last sentence): replace "2*epsilon*gamma/(1-gamma)" with "2*epsilon" (Zongzhang Zhang)
* Sec. 4.7.1 (second to last sentence): drop "and m" (Hamza El-Saawy)
* Fig. 6.6: some of the alpha vectors did not print correctly (noted by Yi-Chun Chen); the figure should look like this: <img src="alphavectors.png" alt="fig.6.6" width="300">
* Sec. 6.4.5 (second sentence): replace "each belief state B" with "each belief state in B" (Zongzhang Zhang)
* Ch. 7: references 12, 15, 38, and 63 should have "POMDPS" and "MDPS" changed to "POMDPs" and "MDPs" (Zongzhang Zhang)
* Eq. 6.31: should be $\sum_s b(s) \sum_{s'} O(o \mid s', a)T(s' \mid s, a)$ (Junzi Zhang)

These items will be fixed in the 6th printing:

* Alg. 4.1: U should have \pi as a superscript everywhere (Benjamin Antin)
* Eq. 4.24 and 4.27: The rightmost Ta should be transposed (Tim Wheeler)
* Alg 2.1, line 2: Drop the subscript on the s
* Alg 4.9, line 13: for consistency arg max should be over A(s) rather than all of A
* Eq. 4.36: It should be explained that if N(s,a) = 0, then the exploration bonus is treated as infinity (Tim Wheeler)
* Eq. 6.15-6.17: The Kalman filter equations should look like [this](kalman-filter.PNG) (Tim Wheeler)
* Table 10.2: ft/s in the rightmost column should be ft/min (Cem Polat)
* Sec. 1.5: `[10]` should be swapped with `[11]` (Vladislav Ankudinov)
* Sec. 4.7.3: two instances of $P(\lambda; \theta)$ should be $P(\lambda \mid \theta)$ for consistency (Ross Alexander)
* After eq. 4.2: "is worth" should be "are worth" (Brad Rafferty)
* Immediately before eq. 5.31: the $n$ should be $m$ to be consistent with eq. 5.31 (Kyu-Young Kim)
* First sentence of 5.2.2: change "Q" to "U"
* Sec. 4.3.1 last sentence: "four" should be "five" (Preston Rogers)
* Eq. 4.25: The T_s immediately after the inverse should be T_a (Allan Li)
* Alg. 6.2: sampling state from b should be within the repeat loop so lines 4 and 5 should be swapped (Tim Wheeler)
* Eq. 6.1: drop the t subscripts (Kyu-Young Kim)

These items will be fixed in a future printing:
* For consistency, algorithms in Ch. 7 should use U instead of V.
