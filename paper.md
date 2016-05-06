---
title: 'Application Skeleton: Generating Synthetic Applications for Infrastructure Research'
tags:
  - computational science
  - data science
  - application modeling
  - system modeling
  - performance modeling
  - parallel and distributed systems
authors:
 - name: Zhao Zhang
   orcid: 0000-0001-5921-0035
   affiliation: AMPLab and BIDS, University of California, Berkeley
 - name: Daniel S. Katz
   orcid: 0000-0001-5934-7525
   affiliation: National Center for Supercomputing Applications, University of Illinois Urbana-Champaign
 - name: Andre Merzky
   orcid: 0000-0002-7228-4327
   affiliation: RADICAL Laboratory, Rutgers University
 - name: Matteo Turilli
   orcid: 0000-0003-0527-1435
   affiliation: RADICAL Laboratory, Rutgers University
 - name: Shantenu Jha
   orcid: 0000-0002-5040-026X
   affiliation: RADICAL Laboratory, Rutgers University
date: 5 May 2016
bibliography: paper.bib
---

# Summary
Application Skeleton is a simple and powerful tool to build synthetic applications with runtime and I/O close to that of the real ones. It allows the computer scientists to bypass the obstacles encountered when accessing and building the real applications to 
verify the effectiveness of their new system design. Application Skeleton guarantees that the effective work on synthetic applications will also be applicable to the real applications.

Application Skeleton can generate bag-of-task, (iterative) map-reduce, and (iterative) multistage workflow applications. The generated applications are compatible with workflow system such as Swift [@SWIFT07, @SWIFT09, @SWIFT11] and Pegasus [@PEGASUS04, @PEGASUS05], as well as the ubiquitous UNIX shell.
The application can also be in the generic JSON object that can be used by other systems such as the AIMES [@AIMES15] middleware.
# References
