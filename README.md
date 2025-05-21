# CS5800-Assignment-4-solution

Download Here: [CS5800: Assignment 4 solution](https://jarviscodinghub.com/assignment/cs5800-assignment-4-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. (30 points)
Suppose you are a high-level manager in a software firm and you are managing n software projects.
You are asked to assign m of the programmers in your firm among these n projects. Assume that all of
the programmers are equally competent.
After some careful thought, you have figured out how much benefit i programmers will bring to project j.
View this benefit as a number. Formally put, for each project j, you have computed an array Aj [0..m] where
Aj [i] is the benefit obtained by assigning i programmers to project j. Assume that Aj [i] is nondecreasing
with increasing i. Further make the economically sound assumption that the marginal benefit obtained
by assigning an ith programmer to a project is non-increasing as i increases. Thus, for all j and i ≥ 1,
Aj [i + 1] − Aj [i] ≤ Aj [i] − Aj [i − 1].
(a) Design a greedy algorithm to determine how many programmers you will assign to each project such
that the total benefit obtained over all projects is maximized. Your answer should be in the form of
a sequence of clearly stated steps. Pseudo-code is optional.
(b) Justify the correctness of your algorithm and analyze its efficiency in space and time.
2. (30 points)
The Museum of Fine Art is planning to construct a new wing to showcase paintings of contemporary
art. The new wing consists of a single, long corridor. Paintings roughly of size 2×2 feet will be hung along
both walls of this corridor. Their centers are placed along distances x1, x2, …xn from the start of their
respective walls, all at the same height.
1
An architect is trying to design how to light this corridor. She has to fit linear panels of light (fluorescent
tube lights) above each wall, along it. Each panel of light reliably provides light within a horizontal span
of m feet at the height at which the paintings are hung (same for all panels). Each painting is lit if it is
within the horizontal span of at least one panel. Panels of lights are significantly longer than the span of
each painting (m  2), so she is ready to assume that each painting is a dot at its center. Her problem is
to place a minimum number of panels of lights along and above each wall so that each painting is lit.
(a) State the technical problem (i.e. state the actual computational problem without context, in a way
that it can be applied to any other context).
(b) Provide an efficient algorithm to compute the centers of the panels of light along one wall, obeying
the above constraints. Your algorithm should be in the form of a sequence of clear and precise steps.
Pseudo-code is optional.
(c) Justify the correctness of your algorithm and analyze its efficiency in space and time.
3. (30 points)
“Elixir of Life” is a milk bank that provides mother’s milk to newborn babies in their critical first few
months of life. They accept donations from mothers, homogenize and pasteurize it and then package them
into vials of 1, 5, 10, 20 and 50 ounces. Then they supply to local hospitals for a fee to cover their costs
for processing and packaging, which must be done in extremely hygienic conditions. As the milk bank is
sustained only through donations, there are a limited number of vials of each size.
(a) When new parents come to the bank with a prescription of m ounces, the bank must dispense the
amount to them. Note that due to hygiene issues the bank is not allowed to open the packaged vial
to dispense part of an amount. However you may assume that m is an integral number. Design an
algorithm to dispense exactly m ounces using the minimum number of vials. Your answer should
include a short description about why your algorithm returns the optimal answer. Your answer must
be in the form of a sequence of clear and precise steps. Pseudo-code is optional.
(b) Justify the correctness of your algorithm and analyze its efficiency in space and time.
(c) How will you know if dispensing the amount is even possible?
