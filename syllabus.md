---
layout: post
title: "Syllabus"
published: true
---

This syllabus discusses the main motivation and topics to be covered in the course. 

Specific course policies can be found [here](https://rob-p.github.io/CSE373S18/policies.html).

Administrative information about the course can be found [here](https://rob-p.github.io/CSE373S18/administrative.html).

Overview
============

This course is meant to teach you how to rigorously and formally analyze
algorithms, as well as how to go about designing algorithms to solve problems
you may encounter. Specifically, one of the main takeaways from this course
should be a new way of thinking about computational problems and procedures for
solving them. Some people, who do not have previous experience in thinking in
this way, may initially find the course difficult. This is OK, and, in fact,
intended. New ways of thinking about things are often challenging at first.
However, as we cover more material and as you practice your new skills on the
homework sets, this type of formal analysis and design should become easier.
This being said, you are expected to have satisfied
the [pre-requisites](#prereq) for this course, and mastery of that material is
assumed.

We will follow the required text, [Algorithm Design](https://www.amazon.com/Algorithm-Design-Kleinberg-published-Addison-Wesley/dp/B00E31S1LW/ref=sr_1_10?s=books&ie=UTF8&qid=1516546594&sr=1-10&keywords=Algorithm+Design) by Kleinberg and Tardos, quite closely in the course, though I don't intend to cover everything in the book. Also, we may cover a few topics that are not in the book (particularly when we get to Dynamic Programming), and for these, relevant reference materials will be posted on the course page. If you are interested in alternative expositions of relevant material, I can also recommend the ``Other algorithm resources'' linked in the left column of this page.

Pre-requisites
==================
<a name="prereq"></a>

The pre-requisites for this course are AMS 210 or Mat 211; CSE 214 or CSE 260.

Objectives
============

The main objective of this course will be to provide you with an overview of the
major categories of algorithm design and analysis techniques. Later in the
course, we will also cover introductory concepts in complexity theory and
approximation algorithms. If time permits, we may also touch upon randomized
algorithms. I will generally assume that everyone is faimiliar with basic
computational and algorithmic ideas, and I expect to move fairly quickly through
the introductory material (Ch 1 — 3). It is important to note that this _is not
a programming course_. The goal of this course is to teach you about the design
and analysis of algorithms, and we will focus much more on e.g., proving that an
algorithm is correct or efficient than on actually implementing it. This being
said, **simply because there isn’t a programming assignment for a certain
algorithm doesn’t mean that you shouldn’t attempt to implement it**. Often
times, writing a concrete implemenation of an algorithm that you only undestand
abstractly is one of the best ways to really understand it and familarize
yourself with it.
 
Topics & Schedule (tentative)
====================================

The following is a list of the topics I intend to cover this semester.  This list is _tentative_, and is subject to revision based on how quickly we make progress.

* Week 1 (Jan 22.)
   - Introduction, administration, what are algorithms? Algorithmic thinking.
   - Stable Matching (proof of correctness, analyzing termination, etc.).
   
* Week 2 (Jan 29.)
   - Landau notation (Big O and friends), worst-case analysis (Ch 2).
   - Introduction to graphs / graph search (Ch 3).

* Week 3 (Feb 5.)
   - Greedy algorithms I 
   - interval scheduling
   - shortest path, MST

* Week 4 (Feb 12.)
   - Greedy algorithms II
   - union/find, clustering, Huffman codes
   
* Week 5 (Feb 19.)
   - Midterm 1
   - Divide-and-Conquer I

* Week 6 (Feb 26.)
   - Divide-and-Conquer I cont. (sorting and selection)
   - Divide-and-Conquer II (integer multiplicationl, matrix multiplication)
   
* Week 7 (Mar 5.)
   - Dynamic Programming I (weighted interval scheduling)
   
* Week 8 (Mar 12.)
   - Dynamic Programming II (string alignment / edit distance, RNA-folding)
      
* Week 9 (Mar 19.)
   - Dynamic Programming III (linear space alignment, shortest paths in a graph)
   
* Week 10 (Mar 26.)
   - Midterm 2
   - Viterbi (tentative)

* Week 11 (Apr 2.)
   - Network Flow I (Flow graphs, Max Flow / Min Cut)
   - Network Flow II (Circulations with demands)

* Week 12 (Apr 9.)
   - Network Flow III (Applications: Bipartite matching, disjoint paths, etc.)

* Week 13 (Apr 16.)
   - Computational tractability, NP-hardness & NP-completeness
   - NP-complete problems & polynomial time reductions
   
* Week 14 (Apr 23.)
   - Approximation algorithms 
   - Set /vertex cover, knapsack
   
* Week 15 (Apr 30.)
  - Review and wrap-up **Final day of class**: Friday, May 4, 2018 (May the fourth be with you)
  
* **Final Exam**: Monday May 14, 2018 (2:15PM &mdash; 5:00PM).  
