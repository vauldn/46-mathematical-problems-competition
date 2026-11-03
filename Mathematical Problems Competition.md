# Mathematical Problems Competition / Конкурс математических задач

English: [Problems](#en-problems) · [Competition Rules](#en-rules) · [Solution Requirements](#en-solution-requirements) · [Notes on the Problems](#en-notes)

Русский: [Задачи](#ru-problems) · [Правила конкурса](#ru-rules) · [Уточнения по решению задач](#ru-solution-requirements) · [Примечания к задачам](#ru-notes)

---

### Brief competition rules

Here is a list of long-standing mathematical problems whose statements are understandable to a school student, but whose solutions have not yet been found. This is an open competition for AI, humans, and teams.
Solve the problems (individual parts are welcome too) and publish your solutions openly!
Based on recognition of the solutions' correctness by the scientific community, the competition organizer decides whether to award points and close the corresponding problems or individual parts.
As recognized solutions emerge, a results chart will be updated to show how many points each participant has earned.

[Competition Rules](#en-rules) · [Solution Requirements](#en-solution-requirements) · [Notes on the Problems](#en-notes)

<a name="en-problems"></a>

## Mathematical Problems

46 problems · 68 questions and parts · 50 points.

Natural numbers are 1, 2, 3, …, unless explicitly stated otherwise. All answers must be justified.

### 1. Odd perfect numbers

(ID: 2).

A natural number is called perfect if it equals the sum of all its positive divisors other than itself. For example, \(6=1+2+3\).

**a) (1 point)** Does an odd perfect number exist?

**b) (1 point)** Find at least one odd perfect number, or prove that none exist.

### 2. Twin primes

(ID: 8).

Twin primes are two prime numbers that differ by 2. Examples include 3 and 5, 11 and 13, and 17 and 19.

**(2 points)** Are there infinitely many pairs of twin primes?

### 3. Goldbach's conjecture

(ID: 5).

The two prime numbers in the sum may be equal, for example 4 = 2 + 2.

**(2 points)** Can every even natural number greater than 2 be written as the sum of two prime numbers?

### 4. The Collatz conjecture

(ID: 10).

Take any natural number. If it is even, divide it by 2; if it is odd, multiply it by 3 and add 1. Repeat these steps with each resulting number.

**(2 points)** Is it true that, whatever natural number we start with, we will eventually reach 1?

### 5. Sloane's decimal persistence problem

(ID: 25).

Take a natural number, multiply all its digits together, and repeat with the result until a single-digit number is reached. Use decimal notation.

A number that already has one digit requires 0 steps.

**a) (0.7 points)** Find a number that requires **more than 11 steps**, and determine exactly how many, or prove that no such number exists.

**b) (0.3 points)** Is there a natural number \(K\) such that every starting natural number becomes a single-digit number in at most \(K\) steps?

### 6. The number 196

(ID: 11).

Take a natural number, reverse its digits, and add the resulting number to the original. Repeat with the result. A number that reads the same in both directions is called a palindrome.

Here, we call a natural number a Lychrel number if this process never leads from it to a palindrome.

Use decimal notation. Leading zeros after reversal do not change the number's value. If the starting number is already a palindrome, we count it as reaching a palindrome in zero steps.

**a) (0.7 points)** Will a palindrome ever be reached if we start with **196**?

**b) (0.3 points)** Find a **Lychrel number**, or prove that none exist.

### 7. Packing equal squares — Erdős and Graham

(ID: 38).

You are given identical squares of side length 1. Each may be moved and rotated through any angle. All the small squares must fit entirely inside a larger square. They may touch but must not overlap. Gaps may remain between them; the squares may not be cut.

**a) (0.3 points)** What is the smallest side length of a square that can hold 20 unit squares? Find an optimal arrangement.

**b) (0.7 points)** What is the smallest side length of a square that can hold 26,031,913 unit squares? Find an optimal arrangement.

### 8. Pancake flipping — Goodman's problem

(ID: 30).

You have a stack of pancakes of different diameters. In one move, you may flip any top portion of the stack. The goal is to arrange the pancakes from largest at the bottom to smallest at the top.

You may flip a single pancake, several pancakes at the top, or the entire stack. The order of the pancakes in the flipped portion is reversed; the lower portion stays in place. It does not matter which side of a pancake faces up.

**a) (0.3 points)** What is the smallest number of flips guaranteed to be enough to sort any stack of 20 pancakes?

**b) (0.7 points)** What is the smallest number of flips guaranteed to be enough to sort any stack of 1933 pancakes?

### 9. Splitting a heap into two unequal heaps — Grundy's game

(ID: 45).

Start with a single heap of n stones. Two players take turns. On each turn, a player chooses any existing heap and splits it into two nonempty heaps containing different numbers of stones. Stones are not removed, and heaps are not combined. A player who cannot move loses. The game ends when every heap contains one or two stones.

**(1 point)** Is it true that, for every \(n>1222\), the first player can guarantee a win, no matter how the opponent plays?

### 10. Ramsey numbers

(ID: 23).

Any two guests either know each other or do not.

If one guest knows another, the other guest knows them too. A group of "pairwise acquaintances" means that every two people in the group know each other; a group of "pairwise strangers" means that no two people in the group know each other.

**a) (0.3 points)** What is the smallest number of guests that guarantees either five pairwise acquaintances or five pairwise strangers among them?

**b) (0.7 points)** What is the smallest number of guests that guarantees either six pairwise acquaintances or six pairwise strangers among them?

### 11. Sorting weights with the fewest weighings

(ID: 44).

You have several weights, no two of which weigh the same. In one weighing, you may place exactly one on each pan of a balance and find out which is heavier.

Their weights are not known in advance. The balance only tells you which is heavier, without giving numerical values. You may choose the next pair based on the results of previous weighings.

**a) (0.3 points)** What is the smallest number of weighings guaranteed to be enough to arrange 23 weights from lightest to heaviest?

**b) (0.7 points)** What is the smallest number of weighings guaranteed to be enough to arrange 1887 weights from lightest to heaviest?

### 12. Toeplitz's conjecture

(ID: 15).

Consider a continuous closed curve with no self-intersections: during one complete traversal, the only point visited twice is the starting point, at the very end. The curve does not touch itself or retrace any part.

The four vertices of the square must be distinct, and its side length must be positive. All four vertices must lie on the curve; the sides of the square need not follow the curve or stay within the region it encloses.

**(1 point)** Is it true that every continuous closed curve in the plane with no self-intersections contains four points that are the vertices of a square?

### 13. Erdős's unit distance problem

(ID: 12).

Arrange n distinct points in the plane to obtain as many pairs of points as possible at a distance of exactly 1 from each other.

Each pair is counted once. The points are distinct; there are no other restrictions on their arrangement. The line segments joining the pairs may cross.

**a) (0.3 points)** How should 25 points be arranged to maximize the number of such pairs? What is this maximum?

**b) (0.7 points)** How should 1946 points be arranged to maximize the number of such pairs? What is this maximum?

### 14. A square made of zeros and ones

(ID: 31).

**(1 point)** Find a perfect square whose decimal representation contains only zeros and ones, with at least two ones, or prove that no such square exists.

### 15. The Brocard–Ramanujan problem

(ID: 33).

Choose a natural number n, multiply all the natural numbers from 1 to n, and add 1.

The result is known to be the square of an integer for n = 4, 5, 7.

**(1 point)** Find at least one more value of n for which the result is the square of an integer, or prove that there are no others.

### 16. Recamán's sequence

(ID: 27).

Start with 0. At the first step, try subtracting 1 from the last number written down; at the second step, try subtracting 2; at the third, 3; and so on. If the result of the subtraction is at least 0 and has not appeared in the sequence before, write it down. Otherwise, add the step number to the last number written down and record the resulting sum.

This gives the sequence:

0, 1, 3, 6, 2, 7, 13, 20, 12, 21, 11, ...

The initial number 0 has index 0, the next term 1 has index 1, and so on.

Record the result of addition even if that number has already appeared. Record the result of subtraction only if it has not appeared before.

**a) (0.4 points)** Give the index of a term equal to 852,655, or prove that there is no such term.

**b) (0.6 points)** Does every natural number appear in this sequence?

### 17. A Smarandache prime

(ID: 48).

Choose a natural number \(n\) and write the decimal representations of all the natural numbers from 1 to \(n\), inclusive, one after another without spaces.

For example, \(n=3\) gives 123, \(n=5\) gives 12345, and \(n=10\) gives 12345678910.

**(1 point)** Find at least one natural number \(n\) for which the number produced in this way is prime, or prove that no such \(n\) exists.

### 18. Palindromic primes

(ID: 32).

A palindrome is a number whose decimal representation reads the same from left to right and from right to left. For example, 101 and 131 are palindromic primes.

**a) (0.5 points)** Are there infinitely many palindromic primes in decimal notation?

**b) (0.5 points)** Are there infinitely many primes whose decimal representation consists only of ones?

### 19. Sophie Germain primes

(ID: 19).

**(1 point)** Are there infinitely many primes p for which \(2p+1\) is also prime?

### 20. Fibonacci primes

(ID: 20).

The Fibonacci sequence starts with 1, 1. Each subsequent number is the sum of the previous two:

1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, ...

**(1 point)** Are there infinitely many prime numbers in the Fibonacci sequence?

### 21. Landau's first problem — primes of the form \(n^2+1\)

(ID: 6).

**(1 point)** Are there infinitely many natural numbers n for which n² + 1 is prime?

### 22. Euclid primes

(ID: 39).

Multiply the first consecutive prime numbers and add 1.

Use exactly the first consecutive primes: 2; then 2 and 3; then 2, 3, 5; and so on. You may not choose primes arbitrarily or skip any.

**(1 point)** Can infinitely many prime numbers be obtained in this way?

### 23. Amicable numbers

(ID: 1).

**(1 point)** Are there infinitely many pairs of distinct natural numbers such that the sum of the positive divisors of each number, excluding the number itself, equals the other number?

### 24. The perfect cuboid

(ID: 9).

Imagine a rectangular box. All three of its dimensions must be greater than 0. A face diagonal joins opposite vertices of a single face; a space diagonal passes through the inside of the box and joins opposite vertices of the box.

**(1 point)** Find the edge lengths of a rectangular box whose edges, face diagonals, and space diagonals all have integer lengths, or prove that no such box exists.

### 25. Legendre's conjecture

(ID: 7).

**(1 point)** Is there always at least one prime between the squares of any two consecutive natural numbers?

### 26. Mersenne primes

(ID: 3).

**(1 point)** Are there infinitely many primes of the form \(2^p-1\), where \(p\) is prime?

### 27. Fermat primes

(ID: 4).

Fermat primes are prime numbers that are 1 greater than a power of two with a positive integer exponent. Five such numbers are known: 3, 5, 17, 257, and 65537.

**a) (0.7 points)** Find another Fermat prime, or prove that there are only five.

**b) (0.3 points)** Are there infinitely many Fermat primes?

### 28. Gilbreath's conjecture

(ID: 16).

Write all the prime numbers in increasing order. In the next row, write the absolute differences between adjacent numbers. Repeat this operation with the new row, and so on.

The absolute difference is the larger number minus the smaller; for equal numbers, it is 0.

For example, the first few rows begin as follows:

```text
2  3  5  7  11  13  ...
1  2  2  4   2  ...
1  0  2  2  ...
1  2  0  ...
```

**(1 point)** Is it true that every row except the first always begins with 1?

### 29. Singmaster's conjecture

(ID: 24).

Build Pascal's triangle: the first row contains the number 1. Each subsequent row contains one more number than the previous row. It begins and ends with 1, and every number between them is the sum of the two numbers just above it, to the left and right, in the previous row.

All positions are counted, including symmetric ones.

The first few rows of the triangle:

```text
        1
      1   1
    1   2   1
  1   3   3   1
1   4   6   4   1
```

**a) (0.5 points)** Find a number other than 1 that occurs more than 8 times in Pascal's triangle, or prove that no such number exists.

**b) (0.5 points)** Is there a natural number K such that every number other than 1 occurs at most K times in the infinite Pascal's triangle?

### 30. Colored arithmetic progressions — van der Waerden numbers

(ID: 35).

The natural numbers from 1 to N are colored using several colors. The goal is to find numbers of the same color that form an arithmetic progression, meaning that the gap between successive numbers is constant.

Each number receives exactly one color from the given palette: two colors in part a, twelve in part b. You do not have to use every color. The chosen seven or twelve numbers must be distinct, and the common difference must be a positive integer. They need not be consecutive numbers in the original list; you may choose the starting number and the common difference after the coloring is complete. A guarantee for every coloring is required, rather than a probability for randomly chosen colors.

**a) (0.3 points)** What is the smallest N that guarantees that, in every coloring of the numbers from 1 to N with two colors, there are seven numbers of the same color forming an arithmetic progression?

**b) (0.7 points)** What is the smallest N that guarantees that, in every coloring of the numbers from 1 to N with twelve colors, there are twelve numbers of the same color forming an arithmetic progression?

### 31. A magic square of squares — Lucas's problem

(ID: 26).

**(1 point)** Fill a 3×3 grid with nine distinct squares of positive integers so that the sums in every row, every column, and both diagonals are equal, or prove that this is impossible.

### 32. Powers of two from ones — Selfridge's problem

(ID: 28).

You may not join ones together to form numbers such as 11, 111, and so on. Each one is used as a separate number 1.

Count every one in the fully written-out expression. If part of the expression is repeated, all the ones in that part are counted again each time.

For example, 2³ = (1 + 1) · (1 + 1) · (1 + 1) uses 6 ones. In this way, the power 2ⁿ can be written using 2n ones. The question is whether fewer ones can be used for at least one n.

**(1 point)** Find an expression for some power \(2^n\), where \(n\) is a natural number, using fewer than \(2n\) ones and only addition, multiplication, and parentheses, or prove that no such expression exists.

### 33. Consecutive numbers with the same number of divisors — a generalization of the Erdős–Mirsky problem

(ID: 37).

For example, 33, 34, and 35 have the same number of positive divisors: four each.

Count all positive divisors, including 1 and the number itself. The number of divisors must be the same within a given run; it may differ between runs. A run is identified by its first number. Runs may overlap and may be parts of longer runs.

**a) (0.2 points)** Find 24 consecutive natural numbers with the same number of positive divisors, or prove that no such run exists.

**b) (0.3 points)** Are there infinitely many runs of 24 consecutive natural numbers with the same number of positive divisors?

**c) (0.5 points)** For every natural number n, can we find n consecutive natural numbers that all have the same number of positive divisors?

### 34. The Euclid–Mullin sequence

(ID: 29).

Start with 2. To obtain the next number, multiply all the terms of the sequence written so far, add 1, and choose the smallest prime divisor of the result. Then repeat.

This gives the sequence:

2, 3, 7, 43, 13, 53, 5, 6221671, ...

The initial number 2 has index 1, the next term 3 has index 2, and so on.

**a) (0.3 points)** Give the index of a term equal to 41, or prove that there is no such term.

**b) (0.7 points)** Does every prime number appear in this sequence?

### 35. The Erdős–Moser problem

(ID: 14).

Raise all the natural numbers from 1 to n to the same power k, where k is a natural number, and add the results. Can the result equal (n + 1) raised to the same power k?

One example is known: 1 + 2 = 3. It corresponds to n = 2 and k = 1. An equality counts as different if it comes from a different pair of natural numbers n and k.

**(1 point)** Find at least one more such equality, or prove that there are no others.

### 36. The Erdős–Mollin–Walsh conjecture

(ID: 42).

Call a natural number powerful if every prime in its prime factorization occurs at least twice, or if the number is 1. For example, 8 = 2³ and 36 = 2² · 3² are powerful, but 12 = 2² · 3 is not.

**(1 point)** Find three consecutive natural numbers that are all powerful, or prove that no such triple exists.

### 37. Divisibility of products of adjacent blocks — Erdős–Straus

(ID: 43).

Let n and k be natural numbers. Take 2k consecutive natural numbers, starting with n. Split them into two groups of k numbers: the first k and the next k.

In part b, k may be chosen separately for each n.

For example, when n = 3 and k = 4, the first group is 3, 4, 5, 6, and the second is 7, 8, 9, 10. Their products are 360 and 5040; the second is divisible by the first: 5040 ÷ 360 = 14.

**a) (0.3 points)** For n = 36, can we choose a natural number k such that the product of the numbers in the second group is divisible by the product of the numbers in the first group, with no remainder? Find such a k, or prove that none exists.

**b) (0.7 points)** Can such a k be chosen for every natural number n?

### 38. Conway's number game — Sylver Coinage

(ID: 36).

Two players take turns naming positive integers. A player may not name a number that can already be obtained by adding previously named numbers, with each summand allowed to be repeated as often as desired. The history of named numbers is shared by both players; a previously named number may not be named again either. The player who names 1 loses.

There is no fixed upper bound on the numbers. A new move may be smaller or larger than the previous one.

For example, if only 4 and 7 have been named so far, then 8 = 4 + 4, 11 = 4 + 7, and 14 = 7 + 7 are forbidden, but 5 is still allowed.

**a) (0.3 points)** Who can guarantee a win if the first player starts with 16?

**b) (0.7 points)** Who can guarantee a win if the first player starts with 432?

### 39. The Erdős–Straus conjecture (with Schinzel's generalization)

(ID: 13).

The denominators of the three fractions may be equal. Part b asks: for each chosen numerator m, is there a threshold N such that all denominators n from that point onward work? Different values of m may have different thresholds.

**a) (0.7 points)** For every integer n ≥ 2, can the fraction 4/n be written as the sum of three fractions with numerator 1 and positive integer denominators?

**b) (0.3 points)** For every natural number m, is there a natural number N such that, for all natural numbers n ≥ N, the fraction m/n can be written as the sum of three fractions with numerator 1 and positive integer denominators?

### 40. The area of a right triangle — congruent numbers

(ID: 46).

For example, when n = 6, the triangle with sides 3, 4, and 5 works: its area is 3 · 4 ÷ 2 = 6.

**(1 point)** Find a general method for deciding whether there is a right triangle of area \(n\) whose three side lengths can all be expressed as fractions of integers. For every natural number \(n\), the method must give the correct answer, "yes" or "no," after a finite number of computations. Or prove that no such method exists.

Integer lengths are allowed too: for example, 3 = 3/1.

### 41. Moser's worm problem

(ID: 22).

A worm is any continuous curve in the plane of length 1. Think of it as a flexible thread with no thickness, laid out in the plane.

Call a plane figure a suitable cover if it can completely cover any such worm. The same figure is used for all worms; for each worm, you may choose how to move and rotate it. The figure's shape may not be changed. It may consist of several separate pieces, but all the pieces move together: their relative positions may not be changed.

Consider figures for which area is defined. Only translations and rotations are allowed; mirror reflection is not allowed.

The curve may cross itself. When covering the worm, you may not straighten it or otherwise change its shape.

**(1 point)** Find the greatest number \(S\) such that every suitable cover has area at least \(S\).

### 42. The Hadwiger–Nelson problem (6–7)

(ID: 17).

Color every point of the infinite plane so that any two points at a distance of exactly 1 from each other have different colors.

**(1 point)** What is the minimum number of colors needed: six or seven?

### 43. Illuminating a mirrored room — Straus's problem

(ID: 40).

Consider a flat polygonal room whose walls are all mirrors. A lamp located at a single point emits light in every direction. When light reflects off a wall, the angle of reflection equals the angle of incidence. Both angles are measured from the perpendicular to the wall at the point of reflection.

The room is bounded by a closed polygon with no self-intersections; there are no columns or holes. The room may be nonconvex, for example with alcoves. The lamp is inside the room. Any finite number of reflections is allowed for reaching a point. A ray that hits a vertex exactly stops there.

Zero area does not mean there are no points: for example, a single point or a single line segment has area 0.

**a) (0.3 points)** In every such room, can a single lamp be placed so that the entire unlit part inside the room has area zero?

**b) (0.7 points)** In every such room, can a single lamp be placed so that light reaches every interior point of the room?

### 44. The lonely runner — the Wills–Cusick conjecture

(ID: 18).

There are n runners on a circular track, all starting from the same point at the same time. They run in the same direction at distinct, constant, positive speeds. The claim is that, for each runner, there will be a time when that runner is at least 1/n of the track's length away from every other runner.

Distance is measured along the shorter arc. Different runners may have different suitable times.

**a) (0.3 points)** Is the conjecture true for any 16 runners?

**b) (0.7 points)** Is the conjecture true for every natural number \(n\) of runners?

### 45. The Chow–Robbins game — when to stop tossing a coin

(ID: 34).

Toss a coin: on each toss, the probability of heads is 1/2 and the probability of tails is 1/2. After any toss, you may stop and receive a payoff equal to the proportion of heads among all the tosses made. For example, three heads in five tosses give a payoff of 3/5.

The tosses are independent and free; you may not restart the game and reset its history. There is no fixed limit on the number of tosses. An allowed strategy must end the game with probability 1: the probability of never stopping must be 0.

At least one toss has already been made; the number of heads is an integer from 0 to the total number of tosses, inclusive. Future outcomes are unknown: the decision is based only on tosses already made. The rule must provide an optimal strategy from every allowed state.

For example, if you toss the coin once and stop, the payoff is 1 for heads and 0 for tails. Each outcome has probability 1/2. The expected payoff is 1 · 1/2 + 0 · 1/2 = 1/2. This illustrates how to calculate an expectation; it is not the optimal strategy being requested.

**(1 point)** Find an exact general rule that, for any number of tosses already made and any number of heads obtained, determines after a finite number of computations whether to stop or continue, so as to maximize the expected payoff, or prove that no such rule exists.

### 46. Digit strings in the decimal expansion of π

(ID: 47).

Consider the infinite decimal expansion of π:

3.14159265358979323846...

**a) (0.5 points)** Find the digit string **2357111317192329313741434753596167717379838997** in the decimal expansion of π and give the position of its first digit after the decimal point, or prove that it never occurs.  
(The digits of the target string must appear consecutively, in the specified order, with no gaps. Positions after the decimal point are numbered from 1: the first digit, 1, has position 1; the next digit, 4, has position 2. Any occurrence is acceptable, not necessarily the first.)

**b) (0.5 points)** Is it true that every finite digit string can be found in the decimal expansion of π?

---

<a name="en-rules"></a>

## Competition Rules

### 1. The idea behind the competition

This is an open competition to solve a fixed list of mathematical problems, published once and never expanded. Humans, AI systems, and teams, including mixed teams, may participate.

The competition aims to recognize accepted mathematical results and the contributions of those who obtain them. The points reflect the organizer's subjective interest in the problems and are not a measure of their difficulty.

### 2. How to participate

Choose an open question, solve it, and publish your solution openly. The publication must include the result itself and sufficient justification of its correctness.

Identify the authors and participants in the work. If AI was used, identify it, preferably including the model, its version if known, and the nature of the contributions made by humans and AI.

No particular publication format is required. What matters is that the solution is available for independent study and discussion, and that its publication date can be established.

### 3. Which results count

A result must fully meet the requirements of the relevant question. Depending on the question, this may mean a proof, a disproof, a specific example, an exact value, or a general method of solution.

Partial progress, computational checks of individual cases, or improvements to known bounds do not close a question unless they fully meet its requirements.

### 4. Recognition by the scientific community

The competition relies on solutions whose correctness has been recognized by the scientific community.

Scientific publications, independent checks, substantive assessments by specialists, verifiable computations, and formal proofs may provide grounds for accepting a result. None of these alone guarantees automatic acceptance.

An author's claim that a solution is correct is not sufficient. However, recognition does not require unanimous agreement among all mathematicians.

### 5. Who makes the decision

The organizer personally makes the final decisions on accepting results, closing questions, deciding who receives points, and awarding those points, based on the scientific recognition of the result and its compliance with the problem's requirements.

### 6. Awarding points

Points for each scored question are awarded only once. Once a solution is accepted, the question is marked as closed and no further points are available for it.

If one result fully solves several questions that are still open, all of those questions are closed and their points are added together.

For example, finding an odd perfect number closes both corresponding parts and earns a total of 2 points. If one of the parts is already closed, only the points for the remaining open part are awarded.

Solving one part does not automatically close the others: the result must meet the requirements of each part.

### 7. Priority and authorship

When there are several solutions, the organizer considers the date on which a complete, correct solution was openly published, together with information about priority and authorship accepted by the scientific community. The date on which verification is completed does not, by itself, determine priority.

If a new version was needed to correct a substantial error, the relevant date is the publication date of the version containing a complete solution. Whether an error is substantial is ultimately determined by the organizer, taking the views of the scientific community into account.

Joint results and independently obtained results are considered in light of the circumstances in which they arose. The organizer decides who receives credit for the result.

### 8. Public results

The plan is to publish accepted achievements, their authors and participants, closed questions, points awarded, and links to the evidence supporting acceptance.

There are plans to use these data to create competition tables and charts.

### 9. Correcting errors and resolving disputes

If a substantial error, incorrect attribution, or an earlier result previously unknown to the organizer is discovered after acceptance, the decision may be reconsidered.

The organizer may correct the record, change the recipients of the points, revoke points, and reopen the question if necessary.

### 10. Other cases

The organizer personally resolves situations not covered by these rules, following the same principles: correctness of the result, its scientific recognition, compliance with the question's requirements, and accurate attribution and publication dates.

---

<a name="en-solution-requirements"></a>

## Solution Requirements

In this list of problems, natural numbers mean positive integers: 1, 2, 3, …

All answers must be justified. If a question asks for the greatest or smallest value, you must prove that your answer is exact and cannot be improved. Checking a large number of individual examples does not replace a general proof.

If a question asks you to find an integer, you must give its specific value. You may write the number in decimal notation or express it as the product of a specific natural number and powers of specific prime numbers with nonnegative integer exponents. All factors, bases, and exponents must be explicitly written as decimal integers. Merely proving that the number exists or describing a way to search for it, without giving a specific value, is not sufficient.

---

<a name="en-notes"></a>

## Notes on the Problems

### 37. Divisibility of products of adjacent blocks — Erdős–Straus

(ID: 43).

The sequence [OEIS A375071](https://oeis.org/A375071) uses a convention in which \(n\) is one less than the first number in the block. Our case \(n=36\) therefore corresponds to \(a(35)\) in OEIS.

### 46. Digit strings in the decimal expansion of π

(ID: 47).

The string in part a is obtained by writing all the primes from 2 to 97 one after another.

---

### Краткие правила конкурса

Перед вами список давно известных математических задач, условия которых понятны школьнику, но решения до сих пор не найдены. Это открытый конкурс для искусственного интеллекта, людей и команд.
Решайте задачи (можно отдельный пункт задачи) и открыто публикуйте свои решения!
На основании признания правильности решений научным сообществом организатор конкурса принимает решения о присуждении баллов и закрытии соответствующих задач или их отдельных пунктов.
По мере появления признанных решений будет обновляться диаграмма результатов, показывающая, кто сколько баллов набрал.

[Правила конкурса](#ru-rules) · [Уточнения по решению задач](#ru-solution-requirements) · [Примечания к задачам](#ru-notes)

<a name="ru-problems"></a>

## Математические задачи

46 задач · 68 вопросов и подпунктов · 50 баллов.

Натуральные числа — 1, 2, 3, …, если явно не оговорено иное. Ответы на вопросы требуется обосновывать.

### 1. Нечётное совершенное число

(ID: 2).

Натуральное число называют совершенным, если оно равно сумме всех своих положительных делителей, кроме самого себя. Например, \(6=1+2+3\).

**а) (1 балл)** Существует ли нечётное совершенное число?

**б) (1 балл)** Найдите хотя бы одно нечётное совершенное число или докажите, что таких чисел не существует.

### 2. Простые числа-близнецы

(ID: 8).

Простыми числами-близнецами называются два простых числа, различающихся на 2. Например, 3 и 5, 11 и 13, 17 и 19.

**(2 балла)** Бесконечно ли много пар простых чисел-близнецов?

### 3. Гипотеза Гольдбаха

(ID: 5).

Два простых слагаемых могут совпадать, например 4 = 2 + 2.

**(2 балла)** Любое ли чётное натуральное число больше 2 можно представить в виде суммы двух простых чисел?

### 4. Гипотеза Коллатца

(ID: 10).

Возьмём любое натуральное число. Если оно чётное, разделим его на 2, а если нечётное — умножим на 3 и прибавим 1. Будем повторять эти действия с каждым полученным числом.

**(2 балла)** Правда ли, что при любом начальном натуральном числе мы рано или поздно получим 1?

### 5. Десятичная задача Слоуна

(ID: 25).

Берём натуральное число, перемножаем все его цифры и повторяем действие с результатом, пока не получится однозначное число. Используется десятичная запись.

Для уже однозначного числа требуется 0 шагов.

**а) (0,7 балла)** Найдите число, которому требуется **больше 11 шагов**, и определите, сколько именно, или докажите, что такого числа нет.

**б) (0,3 балла)** Существует ли такое натуральное число \(K\), что любое начальное натуральное число станет однозначным не более чем за \(K\) шагов?

### 6. Число 196

(ID: 11).

Берём натуральное число, записываем его цифры задом наперёд и складываем полученное число с исходным. Повторяем действие с результатом. Число, одинаково читающееся в обе стороны, называется палиндромом.

Числами Лишрел здесь называем натуральные числа, из которых этот процесс никогда не приводит к палиндрому.

Используется десятичная запись. Нули впереди после переворачивания не меняют значение числа. Если начальное число уже является палиндромом, считаем, что палиндром получен без шагов.

**а) (0,7 балла)** Получится ли когда-нибудь палиндром, если начать с **196**?

**б) (0,3 балла)** Найдите **число Лишрел** или докажите, что таких чисел не существует.

### 7. Упаковка одинаковых квадратов — Эрдёш и Грэм

(ID: 38).

Даны одинаковые квадраты со стороной 1. Каждый из них можно сдвигать и поворачивать на любой угол. Все маленькие квадраты должны целиком помещаться в большом квадрате. Они могут соприкасаться, но не перекрываться. Между ними могут оставаться пустоты; разрезать квадраты нельзя.

**а) (0,3 балла)** Какова наименьшая длина стороны квадрата, в который можно поместить 20 единичных квадратов? Найдите оптимальное размещение.

**б) (0,7 балла)** Какова наименьшая длина стороны квадрата, в который можно поместить 26 031 913 единичных квадратов? Найдите оптимальное размещение.

### 8. Переворачивание блинов — задача Гудмана

(ID: 30).

Есть стопка блинов разного диаметра. За один ход можно перевернуть любую верхнюю часть стопки. Нужно расположить блины от самого большого внизу до самого маленького сверху.

Можно перевернуть один блин, несколько верхних блинов или всю стопку. Порядок блинов в переворачиваемой части меняется на обратный; нижняя часть стопки остаётся на месте. Неважно, какой стороной блин лежит вверх.

**а) (0,3 балла)** Какое наименьшее число переворотов гарантированно достаточно для упорядочивания любой стопки из 20 блинов?

**б) (0,7 балла)** Какое наименьшее число переворотов гарантированно достаточно для упорядочивания любой стопки из 1933 блинов?

### 9. Деление кучки на две неравные — игра Гранди

(ID: 45).

Вначале лежит одна кучка из n камешков. Двое ходят по очереди. За ход выбирают любую из имеющихся кучек и делят её на две непустые кучки с разным количеством камешков. Камешки не убирают и кучки не соединяют. Кто не может сделать ход, проигрывает. Игра заканчивается, когда во всех кучках осталось по одному или два камешка.

**(1 балл)** Правда ли, что при любом \(n>1222\) первый игрок может гарантировать себе победу, как бы ни играл соперник?

### 10. Числа Рамсея

(ID: 23).

Любые два гостя либо знакомы друг с другом, либо незнакомы.

Знакомство взаимно. «Попарно знакомые» означает, что знакомы любые двое из выбранной группы; «попарно незнакомые» — что любые двое из неё незнакомы.

**а) (0,3 балла)** Какое наименьшее число гостей гарантирует, что среди них найдутся либо пять попарно знакомых, либо пять попарно незнакомых?

**б) (0,7 балла)** Какое наименьшее число гостей гарантирует, что среди них найдутся либо шесть попарно знакомых, либо шесть попарно незнакомых?

### 11. Упорядочивание гирек за наименьшее число взвешиваний

(ID: 44).

Есть гирьки, все разного веса. За одно взвешивание можно положить ровно одну гирьку на каждую чашу весов и узнать, какая тяжелее.

Веса заранее неизвестны. Весы сообщают только, какая гирька тяжелее, без численных значений. Следующую пару можно выбирать по результатам предыдущих взвешиваний.

**а) (0,3 балла)** Какое наименьшее число взвешиваний гарантированно позволяет расставить 23 гирьки от самой лёгкой до самой тяжёлой?

**б) (0,7 балла)** Какое наименьшее число взвешиваний гарантированно позволяет расставить 1887 гирек от самой лёгкой до самой тяжёлой?

### 12. Гипотеза Тёплица

(ID: 15).

Речь идёт о непрерывной замкнутой линии без самопересечений: при одном полном обходе повторяется только начальная точка в самом конце. Самокасаний и повторно пройденных участков нет.

Четыре вершины квадрата должны быть различны, а его сторона — положительна. Все четыре вершины должны лежать на линии; стороны квадрата не обязаны проходить по этой линии или оставаться в области, которую она ограничивает.

**(1 балл)** Правда ли, что на любой непрерывной замкнутой линии на плоскости без самопересечений можно найти четыре точки, являющиеся вершинами квадрата?

### 13. Задача Эрдёша о единичных расстояниях

(ID: 12).

Нужно расположить на плоскости n различных точек так, чтобы получить как можно больше пар точек на расстоянии ровно 1 друг от друга.

Каждая пара считается один раз. Точки различны; других ограничений на их расположение нет. Отрезки, соединяющие пары, могут пересекаться.

**а) (0,3 балла)** Как расположить 25 точек, чтобы число таких пар было наибольшим? Чему равен этот максимум?

**б) (0,7 балла)** Как расположить 1946 точек, чтобы число таких пар было наибольшим? Чему равен этот максимум?

### 14. Квадрат из нулей и единиц

(ID: 31).

**(1 балл)** Найдите квадрат натурального числа, состоящий в десятичной записи только из нулей и единиц, причём единиц должно быть хотя бы две, или докажите, что такого квадрата не существует.

### 15. Задача Брокара — Рамануджана

(ID: 33).

Выбираем натуральное число n, перемножаем все натуральные числа от 1 до n и прибавляем 1.

Известно, что квадрат целого числа получается при n = 4, 5, 7.

**(1 балл)** Найдите ещё хотя бы одно значение n, при котором получается квадрат целого числа, или докажите, что других таких значений нет.

### 16. Последовательность Рекамана

(ID: 27).

Начнём с числа 0. На первом шаге пробуем вычесть 1 из последнего записанного числа, на втором — 2, на третьем — 3 и так далее. Если результат вычитания не меньше 0 и ещё не встречался в последовательности, записываем его. В противном случае прибавляем номер шага к последнему записанному числу и записываем полученную сумму.

Получается последовательность:

0, 1, 3, 6, 2, 7, 13, 20, 12, 21, 11, ...

Начальное число 0 имеет номер 0, следующий член 1 — номер 1 и так далее.

Результат сложения записываем, даже если такое число уже встречалось. Результат вычитания записываем только тогда, когда он раньше не встречался.

**а) (0,4 балла)** Укажите номер члена последовательности, равного 852 655, или докажите, что такого члена нет.

**б) (0,6 балла)** Встретится ли каждое натуральное число в этой последовательности?

### 17. Простое число Смарандаке

(ID: 48).

Выбираем натуральное число \(n\) и записываем подряд, без пробелов, десятичные записи всех натуральных чисел от 1 до \(n\) включительно.

Например, при \(n=3\) получаем 123, при \(n=5\) — 12345, а при \(n=10\) — 12345678910.

**(1 балл)** Найдите хотя бы одно натуральное число \(n\), для которого число, полученное описанным способом, является простым, или докажите, что такого \(n\) не существует.

### 18. Простые палиндромы

(ID: 32).

Палиндромом назовём число, десятичная запись которого одинаково читается слева направо и справа налево. Например, 101 и 131 — простые палиндромы.

**а) (0,5 балла)** Бесконечно ли много простых палиндромов в десятичной записи?

**б) (0,5 балла)** Бесконечно ли много простых чисел, десятичная запись которых состоит только из единиц?

### 19. Простые Софи Жермен

(ID: 19).

**(1 балл)** Бесконечно ли много простых p, для которых число \(2p+1\) тоже простое?

### 20. Простые числа Фибоначчи

(ID: 20).

Последовательность Фибоначчи начинается с чисел 1, 1. Каждое следующее число равно сумме двух предыдущих:

1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, ...

**(1 балл)** Бесконечно ли много простых чисел в последовательности Фибоначчи?

### 21. Первая проблема Ландау — простые числа вида \(n^2+1\)

(ID: 6).

**(1 балл)** Бесконечно ли много натуральных чисел n, для которых число n² + 1 является простым?

### 22. Простые числа Евклида

(ID: 39).

Перемножаем первые подряд идущие простые числа и прибавляем 1.

Берём именно первые подряд идущие простые: 2; затем 2 и 3; затем 2,3,5 и так далее. Произвольно выбирать или пропускать простые нельзя.

**(1 балл)** Бесконечно ли много простых чисел можно получить таким способом?

### 23. Дружественные числа

(ID: 1).

**(1 балл)** Бесконечно ли много пар разных натуральных чисел, в которых сумма положительных делителей каждого числа, кроме него самого, равна другому числу?

### 24. Совершенный прямоугольный параллелепипед

(ID: 9).

Представьте прямоугольную коробку. Все три её размера должны быть больше 0. Диагональ грани соединяет противоположные вершины одной грани; пространственная диагональ проходит через внутренность коробки и соединяет её противоположные вершины.

**(1 балл)** Найдите длины рёбер прямоугольного параллелепипеда, у которого все рёбра, диагонали граней и пространственные диагонали имеют целые длины, или докажите, что такого параллелепипеда не существует.

### 25. Гипотеза Лежандра

(ID: 7).

**(1 балл)** Между квадратами любых двух соседних натуральных чисел всегда найдётся хотя бы одно простое?

### 26. Простые Мерсенна

(ID: 3).

**(1 балл)** Бесконечно ли много простых чисел вида \(2^p-1\), где \(p\) — простое число?

### 27. Простые Ферма

(ID: 4).

Простые числа Ферма — простые числа, которые на 1 больше степени двойки с положительным целым показателем. Известны пять таких чисел: 3, 5, 17, 257 и 65537.

**а) (0,7 балла)** Найдите ещё одно простое число Ферма или докажите, что их всего пять.

**б) (0,3 балла)** Бесконечно ли много простых чисел Ферма?

### 28. Гипотеза Гилбрета

(ID: 16).

Выпишем все простые числа по возрастанию. В следующей строке запишем абсолютные разности соседних чисел. Затем повторим эту операцию с новой строкой и так далее.

Абсолютная разность — большее число минус меньшее; для равных чисел она равна 0.

Например, первые строки начинаются так:

```text
2  3  5  7  11  13  ...
1  2  2  4   2  ...
1  0  2  2  ...
1  2  0  ...
```

**(1 балл)** Правда ли, что каждая строка, кроме первой, всегда начинается с числа 1?

### 29. Гипотеза Сингмастера

(ID: 24).

Построим треугольник Паскаля: в первой строке стоит число 1. В каждой следующей строке на одно число больше, чем в предыдущей. Она начинается и заканчивается единицей, а каждое число между ними равно сумме двух чисел предыдущей строки, расположенных над ним слева и справа.

Считаются все позиции, включая симметричные.

Первые строки треугольника:

```text
        1
      1   1
    1   2   1
  1   3   3   1
1   4   6   4   1
```

**а) (0,5 балла)** Найдите число, отличное от 1, которое встречается в треугольнике Паскаля более 8 раз, или докажите, что такого числа нет.

**б) (0,5 балла)** Существует ли такое натуральное число K, что любое число, кроме 1, встречается в бесконечном треугольнике Паскаля не более K раз?

### 30. Цветные арифметические прогрессии — числа ван дер Вардена

(ID: 35).

Натуральные числа от 1 до N раскрашивают в несколько цветов. Требуется найти числа одного цвета, образующие арифметическую прогрессию, то есть идущие с одинаковым шагом.

Каждое число получает ровно один цвет из заданной палитры: двух цветов в а, двенадцати в б. Использовать все цвета не обязательно. Выбранные семь или двенадцать чисел различны, шаг — положительное целое число. Они не обязаны быть соседними числами ряда; шаг и начало разрешено выбирать по готовой раскраске. Нужна гарантия для любой раскраски, а не вероятность для случайного выбора цветов.

**а) (0,3 балла)** Какое наименьшее N гарантирует, что при любой раскраске чисел от 1 до N в два цвета найдутся семь чисел одного цвета, образующих арифметическую прогрессию?

**б) (0,7 балла)** Какое наименьшее N гарантирует, что при любой раскраске чисел от 1 до N в двенадцать цветов найдутся двенадцать чисел одного цвета, образующих арифметическую прогрессию?

### 31. Магический квадрат из квадратов — задача Люка

(ID: 26).

**(1 балл)** Заполните таблицу 3×3 девятью различными квадратами положительных целых чисел так, чтобы суммы в каждой строке, каждом столбце и на обеих диагоналях совпадали, или докажите, что это невозможно.

### 32. Степени двойки из единиц — задача Селфриджа

(ID: 28).

Нельзя склеивать единицы в числа 11, 111 и тому подобные. Каждая единица используется как отдельное число 1.

Считаются все единицы в полностью выписанном выражении. Если часть выражения повторяется, все её единицы каждый раз считаются заново.

Например, 2³ = (1 + 1) · (1 + 1) · (1 + 1): использовано 6 единиц. Таким способом степень 2ⁿ записывается с помощью 2n единиц. Спрашивается, удастся ли хотя бы для одного n обойтись меньшим количеством.

**(1 балл)** Найдите представление какой-нибудь степени \(2^n\), где \(n\) — натуральное число, с помощью менее чем \(2n\) единиц, используя только сложение, умножение и скобки, или докажите, что такого представления не существует.

### 33. Последовательные числа с одинаковым количеством делителей — обобщение задачи Эрдёша — Мирского

(ID: 37).

Например, числа 33, 34 и 35 имеют одинаковое количество положительных делителей — по четыре.

Считаются все положительные делители, включая 1 и само число. Количество делителей должно быть одинаковым внутри одной цепочки; в разных цепочках оно может различаться. Цепочку задаёт её первое число. Цепочки могут перекрываться и быть частями более длинной цепочки.

**а) (0,2 балла)** Найдите 24 последовательных натуральных числа с одинаковым количеством положительных делителей или докажите, что такой цепочки не существует.

**б) (0,3 балла)** Бесконечно ли много цепочек из 24 последовательных натуральных чисел с одинаковым количеством положительных делителей?

**в) (0,5 балла)** Можно ли для любого натурального числа n найти n последовательных натуральных чисел, у которых количество положительных делителей одинаково?

### 34. Последовательность Евклида — Маллина

(ID: 29).

Начнём с числа 2. Чтобы получить следующее число, перемножим все уже записанные члены последовательности, прибавим 1 и выберем наименьший простой делитель полученного числа. Затем повторим эту операцию.

Получается последовательность:

2, 3, 7, 43, 13, 53, 5, 6221671, ...

Начальное число 2 имеет номер 1, следующий член 3 — номер 2 и так далее.

**а) (0,3 балла)** Укажите номер члена последовательности, равного 41, или докажите, что такого члена нет.

**б) (0,7 балла)** Встретится ли в этой последовательности каждое простое число?

### 35. Задача Эрдёша — Мозера

(ID: 14).

Возводим все натуральные числа от 1 до n в одну и ту же натуральную степень k и складываем. Может ли получиться число (n + 1), возведённое в ту же степень k?

Известен пример: 1 + 2 = 3. Он соответствует n = 2 и k = 1. Другим считается равенство, полученное при другой паре натуральных чисел n и k.

**(1 балл)** Найдите ещё хотя бы одно такое равенство или докажите, что других нет.

### 36. Гипотеза Эрдёша — Моллина — Уолша

(ID: 42).

Назовём натуральное число мощным, если в его разложении на простые множители каждый множитель встречается хотя бы дважды или если это число равно 1. Например, числа 8 = 2³ и 36 = 2² · 3² — мощные, а 12 = 2² · 3 — нет.

**(1 балл)** Найдите три последовательных натуральных числа, каждое из которых является мощным, или докажите, что такой тройки не существует.

### 37. Делимость произведений соседних блоков Эрдёша — Штрауса

(ID: 43).

Пусть n и k — натуральные числа. Возьмём 2k последовательных натуральных чисел, начиная с n. Разделим их на две группы по k чисел: первые k и следующие k.

В пункте б число k можно выбирать отдельно для каждого n.

Например, при n = 3 и k = 4 первая группа — 3, 4, 5, 6, вторая — 7, 8, 9, 10. Их произведения равны 360 и 5040; второе делится на первое: 5040 : 360 = 14.

**а) (0,3 балла)** Можно ли при n = 36 подобрать такое натуральное k, чтобы произведение чисел второй группы делилось на произведение чисел первой группы без остатка? Найдите такое k или докажите, что его не существует.

**б) (0,7 балла)** Можно ли подобрать такое k при любом натуральном n?

### 38. Числовая игра Конвея — Sylver Coinage

(ID: 36).

Двое по очереди называют положительные целые числа. Нельзя называть число, которое уже получается сложением ранее названных чисел, причём каждое слагаемое разрешено повторять сколько угодно раз. Ранее названные числа общие для обоих игроков; повторять сам ход тоже нельзя. Назвавший 1 проигрывает.

Общего верхнего ограничения на числа нет. Новый ход может быть меньше или больше предыдущего.

Например, если пока названы только 4 и 7, то 8 = 4 + 4, 11 = 4 + 7 и 14 = 7 + 7 называть нельзя, а 5 ещё можно.

**а) (0,3 балла)** Кто может гарантировать победу, если первый игрок начинает с числа 16?

**б) (0,7 балла)** Кто может гарантировать победу, если первый игрок начинает с числа 432?

### 39. Гипотеза Эрдёша — Штрауса (с обобщением Шинцеля)

(ID: 13).

Знаменатели трёх дробей могут совпадать. В пункте б спрашивается: для каждого выбранного числителя m существует ли такой порог N, начиная с которого подходят все знаменатели n? Для разных m пороги могут быть разными.

**а) (0,7 балла)** Для любого ли целого числа n ≥ 2 можно представить дробь 4/n в виде суммы трёх дробей с числителем 1 и положительными целыми знаменателями?

**б) (0,3 балла)** Для любого ли натурального числа m найдётся такое натуральное число N, что при всех натуральных n ≥ N дробь m/n можно представить в виде суммы трёх дробей с числителем 1 и положительными целыми знаменателями?

### 40. Площадь прямоугольного треугольника — конгруэнтные числа

(ID: 46).

Например, при n = 6 подходит треугольник со сторонами 3, 4 и 5: его площадь равна 3 · 4 : 2 = 6.

**(1 балл)** Найдите общий способ определять, существует ли прямоугольный треугольник площади \(n\), длины всех трёх сторон которого можно выразить обыкновенными дробями. Способ должен для любого натурального \(n\) за конечное число вычислений давать правильный ответ «да» или «нет». Или докажите, что такого способа не существует.

Целые длины тоже разрешены: например, 3 = 3/1.

### 41. Червяк Мозера

(ID: 22).

Червяком назовём любую непрерывную линию на плоскости длиной 1. Её можно представить как гибкую нить без толщины, уложенную на плоскости.

Подходящей назовём плоскую фигуру, которой можно полностью накрыть любого такого червяка. Для всех червяков используется одна и та же фигура; для каждого червяка можно выбрать её перенос и поворот. Форму фигуры изменять нельзя. Она может состоять из нескольких отдельных частей, но все части перемещаются вместе: менять их взаимное расположение нельзя.

Рассматриваем фигуры, для которых определена площадь. Разрешены только переносы и повороты; зеркальное отражение не разрешено.

Линия может пересекать сама себя. Самого червяка при накрывании нельзя распрямлять или иначе менять его форму.

**(1 балл)** Найдите наибольшее число \(S\), такое что все подходящие фигуры имеют площадь не меньше \(S\).

### 42. Задача Хадвигера — Нельсона (6-7)

(ID: 17).

Требуется раскрасить все точки бесконечной плоскости так, чтобы любые две точки, находящиеся на расстоянии ровно 1 друг от друга, были разных цветов.

**(1 балл)** Какое наименьшее количество цветов для этого необходимо, шесть или семь?

### 43. Освещение зеркальной комнаты — задача Штрауса

(ID: 40).

Рассмотрим плоскую многоугольную комнату, все стены которой являются зеркалами. Лампа, находящаяся в одной точке, излучает свет во всех направлениях. При отражении света от стены угол отражения равен углу падения. Оба угла измеряются от перпендикуляра к стене в точке отражения.

Комнату ограничивает замкнутый многоугольник без самопересечений; колонн и дыр нет. Комната может быть невыпуклой, например с нишами. Лампа находится внутри комнаты. Для достижения точки разрешено любое конечное число отражений. Луч, попавший точно в вершину, прекращается.

Нулевая площадь не означает отсутствие точек: например, одна точка или один отрезок имеют площадь 0.

**а) (0,3 балла)** В любой ли такой комнате можно выбрать место для одной лампы, чтобы площадь всей неосвещённой части внутри комнаты была равна нулю?

**б) (0,7 балла)** В любой ли такой комнате можно выбрать место для одной лампы, чтобы свет достиг каждой внутренней точки комнаты?

### 44. Одинокий бегун — гипотеза Уиллса — Кьюсика

(ID: 18).

По круговой дорожке одновременно из одной точки стартуют n бегунов. Все бегут в одном направлении с разными постоянными положительными скоростями. Утверждается, что для каждого бегуна наступит момент, когда он будет удалён от каждого другого хотя бы на одну n-ю длины дорожки.

Расстояние измеряется по более короткой дуге. Для разных бегунов подходящие моменты могут быть разными.

**а) (0,3 балла)** Верна ли гипотеза для любых 16 бегунов?

**б) (0,7 балла)** Верна ли гипотеза для любого натурального числа \(n\) бегунов?

### 45. Игра Чоу—Роббинса — когда остановить бросание монеты

(ID: 34).

Бросаем монету: при каждом броске вероятность орла равна 1/2, вероятность решки — 1/2. После любого броска можно остановиться и получить выигрыш, равный доле орлов среди всех сделанных бросков. Например, три орла из пяти бросков дают выигрыш 3/5.

Броски независимы и бесплатны; начинать игру заново со сбросом истории нельзя. Число бросков заранее не ограничено. Допустимая стратегия заканчивает игру с вероятностью 1: вероятность никогда не остановиться равна 0.

Сделан хотя бы один бросок; число орлов — целое от 0 до общего числа бросков включительно. Будущие результаты неизвестны: решение принимается только по уже сделанным броскам. Правило должно давать оптимальную стратегию из каждого допустимого состояния.

Например, если бросить монету один раз и остановиться, выигрыш равен 1 при орле и 0 при решке. Каждый из этих результатов имеет вероятность 1/2. Математическое ожидание выигрыша равно 1 · 1/2 + 0 · 1/2 = 1/2. Это пример вычисления ожидания, а не требуемая оптимальная стратегия.

**(1 балл)** Найдите точное общее правило, позволяющее при любом количестве уже сделанных бросков и любом числе выпавших орлов за конечное число вычислений определить, следует остановиться или продолжать, чтобы математическое ожидание выигрыша было наибольшим, или докажите, что такого правила не существует.

### 46. Последовательности цифр в десятичной записи числа π

(ID: 47).

Рассмотрим бесконечную десятичную запись числа π:

3,14159265358979323846...

**а) (0,5 балла)** Найдите в десятичной записи числа π последовательность цифр **2357111317192329313741434753596167717379838997** и укажите, с какого знака после запятой она начинается, или докажите, что она не встречается.  
(Цифры искомой строки должны идти подряд, в указанном порядке, без пропусков. Знаки после запятой нумеруются с 1: первая цифра 1 имеет номер 1, следующая 4 — номер 2. Подходит любое вхождение, не обязательно первое.)

**б) (0,5 балла)** Правда ли, что в записи числа π можно найти любую конечную последовательность цифр?

---

<a name="ru-rules"></a>

## Правила конкурса

### 1. Идея конкурса

Это открытый конкурс на решение единожды опубликованного и в дальнейшем не пополняемого списка математических задач. Участвовать могут люди, ИИ и команды, в том числе смешанные.

Цель конкурса — отмечать признанные математические результаты и вклад тех, кто их получил. Баллы выражают субъективную оценку интересности задач организатором и не являются оценкой их сложности.

### 2. Как участвовать

Выберите открытый вопрос, получите решение и опубликуйте его в открытом доступе. Публикация должна содержать сам результат и достаточное обоснование его правильности.

Укажите авторов и участников работы. Если использовался ИИ, укажите какой, желательно модель, её версию, если она известна, и характер участия людей и ИИ.

Специальная форма публикации не обязательна. Важно, чтобы решение было доступно для независимого изучения и обсуждения, а дату его публикации можно было установить.

### 3. Какие результаты учитываются

Результат должен полностью отвечать условиям соответствующего вопроса. В зависимости от условия это может быть доказательство, опровержение, конкретный пример, точное значение или общий способ решения.

Частичный прогресс, вычислительная проверка отдельных случаев или улучшение известных оценок не закрывают вопрос, если они не выполняют его требования полностью.

### 4. Научное признание

Конкурс ориентируется на решения, правильность которых получила признание научного сообщества.

Основаниями для зачёта могут служить научные публикации, независимые проверки, содержательные заключения специалистов, проверяемые вычисления и формальные доказательства. Ни один из этих признаков сам по себе не означает автоматического зачёта.

Одного заявления автора о правильности решения недостаточно. При этом признание не требует единогласного согласия всех математиков.

### 5. Кто принимает решение

Окончательное решение о зачёте, закрытии вопросов, получателях и начислении баллов принимает организатор лично, опираясь на научное признание результата и соответствие условиям задач.

### 6. Начисление баллов

За каждый оцениваемый вопрос баллы присуждаются один раз. После зачёта он помечается закрытым и больше не участвует в розыгрыше баллов.

Если один результат полностью решает несколько ещё открытых вопросов, закрываются все эти вопросы и начисляется сумма их баллов.

Например, найденное нечётное совершенное число закрывает оба соответствующих пункта и приносит суммарно 2 балла. Если один из пунктов уже закрыт, начисляются только баллы за оставшийся открытый пункт.

Решение одного подпункта не закрывает остальные автоматически: необходимо, чтобы результат выполнял требования каждого из них.

### 7. Приоритет и авторство

При наличии нескольких решений организатор учитывает дату открытой публикации полного корректного решения и принятые научным сообществом сведения о приоритете и авторстве. Дата завершения проверки сама по себе не определяет приоритет.

Если для исправления существенной ошибки потребовалась новая версия, учитывается публикация версии, содержащей полноценное решение. Существенность ошибки в конечном счёте определяется организатором, опираясь на мнение научного сообщества.

Совместные и независимо полученные результаты рассматриваются с учётом обстоятельств их появления. Организатор определяет, кому зачесть результат.

### 8. Публичные результаты

Планируется публикация зачтённых достижений, их авторов и участников, закрытых вопросов, начисленных баллов и ссылок на основания зачёта.

На этих данных планируется построение таблиц и диаграмм конкурса.

### 9. Исправление ошибок и спорные случаи

Если после зачёта обнаруживается существенная ошибка, неверное указание авторства или ранее неизвестный организатору предшествующий результат, решение о зачёте может быть пересмотрено.

Организатор может исправить запись, изменить получателей баллов, отменить начисление и при необходимости снова открыть вопрос.

### 10. Прочие случаи

Ситуации, не описанные в правилах, организатор разрешает лично, руководствуясь теми же принципами: правильностью результата, его научным признанием, соответствием поставленному вопросу и корректным указанием авторства и даты публикации.

---

<a name="ru-solution-requirements"></a>

## Уточнения по решению задач

В этом списке задач под натуральными числами понимаются целые положительные числа: 1, 2, 3, …

Все ответы необходимо обосновывать. Если требуется найти наибольшее или наименьшее значение, нужно доказать, что указанный ответ точен и улучшить его невозможно. Проверка большого числа отдельных примеров не заменяет общего доказательства.

Если требуется найти целое число, необходимо указать его конкретное значение. Допускается десятичная запись числа или представление в виде произведения конкретного натурального числа и степеней конкретных простых чисел с неотрицательными целыми показателями. Все множители, основания степеней и показатели должны быть явно указаны десятичными целыми числами. Одного лишь доказательства существования числа или указания способа его поиска без предъявления конкретного значения недостаточно.

---

<a name="ru-notes"></a>

## Примечания к задачам

### 37. Делимость произведений соседних блоков Эрдёша — Штрауса

(ID: 43).

В последовательности [OEIS A375071](https://oeis.org/A375071) используется обозначение, в котором \(n\) на единицу меньше первого числа блока. Поэтому нашему случаю \(n=36\) соответствует \(a(35)\) в OEIS.

### 46. Последовательности цифр в десятичной записи числа π

(ID: 47).

Строка из пункта а получается, если записать подряд все простые числа от 2 до 97.
