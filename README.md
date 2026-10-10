# how to start leetcode: a beginner's roadmap from your first Easy problem to pattern recognition, without grinding 500 random questions

Two Sum has a 50%+ acceptance rate. It's the first problem most people open, and a lot of them stare at it for twenty minutes, feel stupid, and close the tab. That reaction is normal and it has almost nothing to do with whether you can code.

The gap isn't intelligence. It's sequence. LeetCode is a problem bank, not a course, and nothing in the interface tells you what to learn first, which ten problems matter, or when to stop guessing and read an editorial. What follows is that missing sequence: a concrete first week, the patterns worth naming, the lists worth following, and what the paid options actually cost so you don't buy something you don't need yet.

## Before problem #1: four things that need to exist

You don't need to "master data structures" first. That advice sends people into three-month tutorial spirals and they never solve anything. You need enough to be dangerous.

1. **Syntax fluency in one language.** Variables, loops, conditionals, functions, and how to iterate a list or array without looking it up.
2. **Two structures you can use without thinking.** An array/list and a hash map or dictionary. Most of the first thirty Easy problems are solved with one of those two.
3. **Rough Big O literacy.** Enough to know that a nested loop over the same array is usually the problem and a hash lookup is usually the fix.
4. **One language decision, made once.**

That last one gets more agonized over than it deserves. Here's the honest comparison:

| Language | Why people pick it | The catch |
| --- | --- | --- |
| Python | Shortest code, easiest syntax to write under pressure | Slower runtime, but it almost never decides a LeetCode submission |
| Java | The language many backend interviews are actually conducted in | Verbose; more typing per idea |
| C++ | Fast, huge standard library (STL) | STeeper learning curve if you're new to it |
| JavaScript | Comfortable if you already build for the web | Less common in DSA-focused prep material |

If you already write one of these at work, use it. Interviewers don't score your language choice, and switching languages to chase "the best one" costs you two weeks of syntax fumbling for zero real gain.

## Your first two weeks, in a specific order

Don't filter by Easy and click whatever looks short. Take these ten, roughly in this order, two or three per session:

| # | Problem | Pattern it teaches |
| --- | --- | --- |
| 1 | Two Sum | Hash map lookups |
| 2 | Valid Parentheses | Stack |
| 3 | Merge Two Sorted Lists | Linked list traversal |
| 4 | Best Time to Buy and Sell Stock | Single-pass array |
| 5 | Valid Palindrome | Two pointers |
| 6 | Reverse Linked List | Iterative and recursive pointer work |
| 7 | Contains Duplicate | Hash set |
| 8 | Maximum Subarray | Kadane's algorithm |
| 9 | Climbing Stairs | Basic dynamic programming |
| 10 | Binary Search | Binary search |

Ten problems, not fifty. The point of week one isn't volume, it's getting comfortable with how the editor behaves, what "submit" actually checks, and how much of a problem is reading comprehension versus code.

**On the actual work of solving one problem:** read the statement twice, and trace the given examples by hand before writing anything. Sketch the approach on paper, including what you plan to return. Then code. Then test the cases nobody showed you — empty input, a single element, duplicates, the largest input the constraints allow. Most failed submissions on Easy problems are edge cases, not wrong algorithms.

**On how long to sit there:** 30 to 45 minutes, then look at the answer. Not 10 minutes (you never build retrieval), and not four hours (you don't learn much from hour three of being stuck). When you do read the editorial, read it for the *why*, close the tab, and rewrite the solution from scratch without looking. Copy-pasting a solution you understand teaches you roughly nothing; retyping it from memory is where the retention happens.

All ten of those problems are free. LeetCode's free tier covers the large majority of the problem bank, the editor, and the discussion boards, which is genuinely enough to start with.

## Week 3 onward: stop collecting problems, start collecting patterns

Here's the shift that separates people who improve from people who plateau at 60 solved problems.

Solving Valid Parentheses isn't the lesson. The lesson is "matching and undoing things in reverse order means a stack," because that same insight solves a dozen problems that don't mention parentheses. Solving Search in Rotated Sorted Array isn't the lesson either. The lesson is "binary search works whenever a property stays monotonic, not just on fully sorted arrays."

One problem, one pattern, is a party trick. Five to eight problems per pattern, done consecutively, is where you start recognizing the pattern before you finish reading the question — which is exactly what a technical interview is testing.

The patterns worth knowing early, roughly in this order: two pointers, sliding window, prefix sums, binary search (including on a predicate, not just a sorted array), stacks including monotonic stacks, queue and deque basics, linked list pointer tricks, tree traversals (DFS and BFS), backtracking, heap/top-K, graph traversal, and then dynamic programming.

DP deserves a warning. It's the pattern where most beginners stall, and it's also the one where pushing through ten problems instead of abandoning at three is the difference between "I can't do DP" and "I can recognize a 1D DP when I see one." Nobody finds it intuitive on the first pass.

## Which list do you follow? Four options, and picking one matters more than picking right

You don't need to invent a curriculum. Several curated lists already exist, and they overlap heavily:

| List | Size | Best for |
| --- | --- | --- |
| Blind 75 | 75, fixed | The minimum viable set if you have under three weeks |
| Grind 75 | Customizable, roughly 50–169 | Fitting practice around an actual schedule; built by Yangshun Tay, author of the Tech Interview Handbook |
| NeetCode 150 | 150 | Pattern-first coverage with video walkthroughs for every problem |
| LeetCode 75 | 75 | The built-in study plan if you want zero setup |

Pick one, finish it, then go company-specific. Collecting four lists and finishing none is a very common way to spend three months.

## Where a structured pattern course fits — and where it doesn't

Everything above can be done for free. The free path has one real weakness: nothing in a problem bank tells you which pattern a problem belongs to. You either figure that out yourself or you look it up in a discussion thread, one problem at a time.

[AlgoMonster](https://algo.monster?fpr=li69) is built in the opposite direction. The curriculum is organized by pattern rather than by problem number, so each pattern comes with a written explanation, a code template, diagrams, and then practice problems for that pattern. It's the same idea as the list-based approach, just pre-assembled and with the visual explanations already built. Its content is written by people who worked at Google and by competitive programmers, and the Pro tier includes unlimited use of an AI assistant plus Speedrun, a timed practice mode.

Worth knowing before you pay:

- Third-party breakdowns of the curriculum put it at roughly 48 patterns. That's the whole point — it's a curated subset, not a 3,000-problem bank.
- Reviews consistently describe the material as text-and-diagram based. There are no video walkthroughs, so if you learn primarily by watching someone solve a problem, this isn't a match.
- Some specialized material, such as Quant Interview Prep developed with external partners, is sold separately.
- There's a free tier with limited access, which is the honest way to test whether the teaching style clicks before you spend anything.

👉 See the current AlgoMonster plans and sale pricing

## All AlgoMonster plans, priced

There's no monthly subscription. The pricing page currently displays two paid plans plus a free tier:

| Plan | What you get | Price | Billing | Get it |
| --- | --- | --- | --- | --- |
| Free | Limited access to a subset of lessons and problems | $0 | No card needed | Start on the free plan |
| Pro – Yearly | All patterns, lessons and problems; unlimited AI assistant; unlimited Speedrun; real questions from top tech companies, updated monthly; 500+ lessons across 6 courses, 1,000+ illustrations, 3,000+ editorials; bonus Foundation Course and Build an LLM Course; member discount on live bootcamps; 12 months of access | $99/year, shown as $8.25/mo (list price displays as $198) | Billed annually | Take the Pro Yearly plan |
| Pro – Lifetime | Everything in the annual plan plus lifetime updates and an internal referral to a top tech company for qualified candidates | $189 one-time (list price displays as $378) | Billed once | Get Pro Lifetime |

A few mechanics that matter more than the headline numbers. Sale pricing on this platform is the normal state of affairs rather than a rare event, so the "$99 vs $198" framing is worth checking directly rather than trusting a cached screenshot. There's a promotion-code field at the checkout, and partner codes do circulate — at least one partner page reports an additional 10% stacking on top of the sale, which would land near $89/year or $170 lifetime if it applies to your cart. Test the code and confirm the final total before you pay.

The judgment call is simple. If you're still working through your first twenty Easy problems, the free tier and the free LeetCode bank are enough, and paying now buys you nothing. If you can reliably solve Easies but freeze the moment a Medium doesn't resemble anything you've seen, that's the pattern-recognition gap, and a pattern-organized curriculum addresses it more directly than another 200 random problems would. The lifetime option is $189 against $99/year, so it only makes sense if you expect to interview more than once in the next few years — which is common, but it isn't everyone.

## The 30-minute rule, and how to use hints without sabotaging yourself

The timer isn't about discipline, it's about calibration. Cap yourself at 30–45 minutes on a Medium, then look. What you do next determines whether the time was wasted:

- Read the reasoning, not just the code. If the explanation says "use a monotonic stack," understand *why* the stack is monotonic.
- Close the solution and re-implement it from an empty editor. This is uncomfortable and it's the step that works.
- Write one line in your notes about the insight that unlocked it, in your own words.
- Reschedule the problem for a redo in about a week.

On AI assistants, there's a real split in how people use them. Asking a model to generate the solution on your first attempt is how you build a habit of not thinking, and it shows up painfully in a live interview where nobody will hand you the answer. Asking it to explain a concept, walk through why a solution is O(n), or check your reasoning *after* you have a working submission is a different activity entirely, and a useful one. The rule of thumb: hints from a machine are fine after you've formed your own approach, not before.

## Track your failures, not your green checkmarks

Solved counts are the least interesting number in your prep. A simple spreadsheet with these columns beats any dashboard:

Problem number and name · date solved · pattern · time taken · solved without help (Y/N) · the key insight in one sentence · redo date

Then once a week, answer three questions: which pattern did I learn this week, which problems took far longer than they should have, and what mistake did I repeat twice? Re-solve two or three problems you previously needed help with, from scratch, no editorial. Push your code to a GitHub repo so the history exists outside the LeetCode editor.

## A 12-week schedule that survives a full-time job

| Weeks | Focus | Realistic target |
| --- | --- | --- |
| 1 | Platform familiarity, 10 Easy problems, one language locked in | 10–15 problems solved |
| 2–4 | Arrays, strings, hash maps, two pointers, sliding window | Finish the first pattern block; start recognizing patterns unaided |
| 5–8 | Trees, graphs, recursion, backtracking, binary search variants | Pick up Mediums without panic; begin DP |
| 9–12 | Dynamic programming, heaps, company-tagged problems, timed sessions | Full timed Mediums in 45 minutes, out loud |

Most learners land in the two-to-four-month range before they feel genuinely ready, and 45–60 focused minutes daily beats a six-hour weekend session followed by nothing. A daily habit of one or two problems, tracked and reviewed, outperforms sporadic binges in every account of this process that's worth reading.

## Mistakes that eat the first month

- Sorting by Easy and clicking whatever looks shortest. That's procrastination wearing a productivity costume.
- Spending ten problems on a pattern and moving on, or spending fifty and never moving on. Five to eight, then next.
- Memorizing solutions. Interviews ask you to explain your reasoning; memorization collapses under a follow-up question.
- Never touching a timer until three weeks before the interview. Speed is a separate skill from correctness.
- Skipping review. Solving a problem once is a warm-up; the third pass is where it sticks.
- Reading every "300 problems or you're not ready" post on the internet. The number depends on the list you chose and the companies you're targeting, and 150 well-understood problems beat 400 skimmed ones.

## When to add contests and mock interviews

Contests are worth entering once you've cleared roughly 50 problems — early enough to be humbling, late enough that you're not just reading problem statements for 90 minutes. Treat them as diagnostic, not as a scoreboard.

Mock interviews belong in the final three to four weeks. The skill being tested there isn't solving; it's narrating your approach, stating assumptions, asking clarifying questions about input size and edge cases, and writing code while someone watches. Practicing that alone in a quiet room is not the same thing, and it's the most common reason strong solvers underperform in real rounds.

One thing worth saying plainly, since it doesn't appear in most roadmaps: LeetCode prep and building real software are separate tracks. Passing interviews requires the first. Getting and keeping a job requires the second. Doing only the first for four months is a defensible, time-boxed trade — as long as you know that's what you're doing, and it ends when the offer does.
