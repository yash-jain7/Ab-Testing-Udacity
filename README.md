# Ab-Testing-Udacity

## Current State

At the time of this experiment, Udacity courses currently have two options on the course overview page: "start free trial", and "access course materials". 

If the student clicks "start free trial", they will be asked to enter their credit card information, and then they will be enrolled in a free trial for the paid version of the course. After 14 days, they will automatically be charged unless they cancel first.

If the student clicks "access course materials", they will be able to view the videos and take the quizzes for free, but they will not receive coaching support or a verified certificate, and they will not submit their final project for feedback.

## Experiment Proposed

Udacity tested a change where if the student clicked "start free trial", they were asked how much time they had available to devote to the course. 

If the student indicated 5 or more hours per week, they would be taken through the checkout process as usual. If they indicated fewer than 5 hours per week, a message would appear indicating that Udacity courses usually require a greater time commitment for successful completion, and suggesting that the student might like to access the course materials for free. At this point, the student would have the option to continue enrolling in the free trial, or access the course materials for free instead.

<img src="Final Project_ Experiment Screenshot.png">

## Experiment Goal

The hypothesis was that this might set clearer expectations for students upfront, thus reducing the number of frustrated students who left the free trial because they didn't have enough time—without significantly reducing the number of students to continue past the free trial and eventually complete the course. If this hypothesis held true, Udacity could improve the overall student experience and improve coaches' capacity to support students who are likely to complete the course.

## Experiment Design

Null hypothesis: Setting clear expectations before enrolling will not reduce the number of furstrated students 

Alternate hypothesis: Setting clear expectations before enrolling will reduce the number of furstrated students, thereby improving student experience

Formulating in mathematical terms:

  1. H0: the change has no effect on the number of students who enroll the free trial.  
  
     HA: the change has effect on the number of students who enroll the free trial.
     
  2. H0: the change has no effect on the number of students who pay after the 14 day trial.
 
     HA: the change has effect on the number of students who pay after the 14 day trial.
     
  3. H0: the change has no effect on probability of students dropping during the free trial.
  
     HA: the change has an effect on probability of students dropping during the free trial
