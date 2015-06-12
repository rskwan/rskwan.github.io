---
title: "Peter Norvig on Building Better Online Courses"
date: 2013-10-02
---

_I took these notes on a talk that Peter Norvig gave at UC Berkeley on October 2, 2013._

## Important Concepts

* One-on-one/mastery learning
* Social/engagement factor
* Data analysis and improvement
* Courseware engineering

## Introduction

* The online learning story begins with revision of AI textbook
* Highlighted passages in books
    * "Out of the top 50 highlighted passages, about 20 were from the Hunger Games."
* Student interaction with data important -- can't get same experience with a static textbook
* Want textbook to be "like a coloring book" -- student should complete it and have the experience of creating something
* Co-teaching AI with Thrun
    * Realized that standard format not really much different from the beginning of the university
    * How can we combine lectures and textbooks to get the best of both?

## What is learning?

* Herb Simon: "Learning results from what the student does and thinks and only from what the student does and thinks. The teacher can advance learning only by influencing what the student does to learn."
* Talked to Hal Abelson from MIT (SICP)
    * "Only need to read one paper": [Bloom, The 2-Sigma Problem](http://www.comp.dit.ie/dgordon/Courses/ILT/ILT0004/TheTwoSigmaProblem.pdf)
    * Keep teaching one-on-one consistently ("tutoring"), not just before the test -- gives significantly better results
    * Motivation for talking to camera in an intimate atmosphere -- Intro to AI MOOC
        * Like "talking to a really smart friend at the bar"

## Why do students stay or go?

* MOOC stats
    * About 500 MOOCs
    * About 10% completion, 45% after first HW, 70% after paying $50
    * Compare to in-person Stanford class: 99%
        * But don't forget about admissions! 99% becomes 6.6%
    * About 6 million students
    * 1/3 NA, 1/3 EU, 1/3 rest
    * 80% college degrees
    * Average age: 30
* Job at Google: provide correct answers to complex questions? Not really.
* Education: the motivation behind going to the search box (the hard part!)
* Motivation, not information is important
    * Willpower
    * Due dates (self-commitment, social norms)
    * Peer support (forums, outside groups)
    * Faculty encouragement (emails)
    * Pride of accomplishment
    * Instrinsic vs extrinsic rewards
* Pattern of successful Coursera courses: ramp up + exponential decay + due dates
* Types of courses
    * synchronous: one chance
        * No self-pacing
    * evergreen: forever
        * No motivation
    * semi-synchronous: assignments due, lectures at own pace
        * Too busy one week? Too bad
    * bus route: assignments due every week, but can "get off the bus" and come back once ready
        * Coursera: multiple offerings of courses
* [Metastudy (VanLehn)](http://www.public.asu.edu/~kvanlehn/Stringent/PDF/EffectivenessOfTutoring_Vanlehn.pdf): intelligent tutoring does about as well as human tutoring
* Review of Online Learning (2010)
    * Online learning conditions result in modestly better performance
    * Positive effects mostly due to additional learning time, not the media
* "What we did"
    * Tailored for the medium (internet)
    * Social
    * Bite-sized
    * Problem-driven -- make students work on and play with the problems
        * But… students don't like to be wrong
* Richard Hamming (via Hal Varian): get psets/exams and write book that teaches them how to solve it
    * Analogy: test-driven development in software engineering

## What's next?

* Commonalities between Thrun, Norvig, Koller, Ng: MOOCs and AI -- interest in looking at data
    * Transcript: 20 bits per year
    * iPod: 192K bits per second
    * Can we get more data out of the student's learning experience?
* Authored multipath sequences
    * Modern Genomics class (Coursera) -- most paths out of many MOOCS, but still not that many options
* Need to find a way to build bigger, deeper learning sequences
* Analogy #1: solitary software development vs collaborative engineering
* Analogy #2: two guys and a camera vs Iron Man 3
* How do we find an optimal middle ground?
* Rethinking "MOOC"
    * Massive? Blended approach is good too
    * Online? Not neceessarily (media not as important)
    * Open? Not needed, as long as people enrolled can participate
    * Class? Can be smaller units of education
* OLA: Online Learning Activity (Appstore?) -- new goal
* Google partnership with EdX: [mooc.org](http://mooc.org)

## Thoughts from Q&A

* Children more motivated when rewarded on basis of quality, not just doing it or no reward at all
* You learn better when you have a question in mind before engaging with the material
* Evaluation should be part of the process/experience, not an end goal
* Types of questions and grading
    * Multiple choice/numerical answers -- easy to code and grade, but may not be ideal (e.g. poetry)
    * Peer grading does fairly well compared to prof grading if the rubric/guidelines is good, taking the mean of the peers' grades
    * Clustering essays, then grading the cluster's center and checking essays that are close to confirm grade (faster method)
* Effects on community colleges and smaller state schools
    * Can offer more courses because of online learning
    * Need physical classes for learning trades (welding, carpentry)
* Online learning can offer education beyond graduation -- colleges could contact former students to inform them of classes from professors
* Best way to learn is teaching self -- why just have work that doesn't have a purpose after it's corrected?
    * Come up with own exercises, explanations, contributions to classes
* How do we individualize classes?
    * Need to understand students' motivation, but computers aren't good at that
    * Support for other tools for learning, not just lectures and textbooks
