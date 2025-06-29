---
layout: default
title: "On Project Euler"
---


Project Euler consists of a set of mathematical problems, the (elegant and often efficient) solutions to which generally require both computation and mathematical insight. 

I came across them more than a decade ago but I never really invested time into solving them as they seemed to offer little "value".

As a first year computer science student at UBC, I felt I was better off spending time on "Leetcode" type of problems instead,  which were much more likely to appear in future classes and/or interviews. However the few problems of Project Euler I did take the time to solve, I enjoyed them thoroughly. But that was many years ago.

Recently, I finished the biography of Leonardo Da Vinci by Walter Issacson and one of the things that stood out most to me was how little effort Leonardo put into disseminating his various discoveries and how uninterested he was in their materialistic value. He was spending countless hours pursuing knowledge simply for the sake of attaining it. The hunt and discovery was the reward - all else mattered very little. As you can expect, I found this puzzling at first but inspiring afterwards. My own reflections on this aspect of Leonardo inspired me to take a look back at Project Euler. 

As a result, I started solving Project Euler problems again and i'm having a wonderful time doing so. The first 50 problems are rated at an easy difficulty of 5 % so you can arrive at a brute-forced solution relatively quickly without much mathematical insight. But the real fun begins after you arrive at the correct answer: you go in search of the most efficient/elegant path to the answer. 

As an example, my favourite problem so far has been number 10: Find the sum of all primes below 2 million. 

You can arrive at the correct answer fairly quickly. My solution - which had already been optimised a decent amount - produced the correct solution in 0.9 second. To put this into context, the most optimal solutions on the website came in at around 0.1 second (for python implementations) - they were all implementations/variations of the Sieve of Eratosthenes.

However, a user by the name of Lucy_hedgehog provided a brilliant and elegant solution - distinct from the rest. They remodeled a prime counting function into a prime summation function and arrived at the solution in sublinear time. Their algorithm was more than a magnitude faster than the next best solution clocking in at 0.004 seconds! Deciphering and finally understanding Lucy_Hedgehog's algorithm proved much more fun than the already enjoyable and satisfying green tick mark you get after entering the correct answer to the problem.

This post is a very long way of saying that maybe I was wrong back then: solving Project Euler problems offers immense value (to me).