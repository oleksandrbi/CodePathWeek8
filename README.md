# CodePathWeek8
# Project 8 - Pentesting Live Targets

Time spent: 8 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection Attack
  
  GIF: 
  
      Link: https://github.com/oleksandrbi/CodePathWeek8/blob/master/BlueSQLI.gif
      
  COMMENTS: 
  
     The Blue site has an SQL injection vulnerability, I noticed that it was on the URL. To test out the vulnerablity I implemented the SLEEP command on the database. I easily just pasted it into the URL and right away the site was taking a much longer time to load up, this is the command I used: ' OR SLEEP(1) -- ' . In addition, the whole process took alot of trial and error before anything worked out for me.   
     
     
Vulnerability #2: Session Hijacking Attack

  GIF: 
  
      Link: https://github.com/oleksandrbi/CodePathWeek8/blob/master/BlueSessionHijacking.gif 
      
  COMMENTS:


## Green

Vulnerability #1: Enumeration Attack

  GIF: 
  
      Link: https://github.com/oleksandrbi/CodePathWeek8/blob/master/GreenEnumerationAttack.gif
      
  COMMENTS: 
  
   

Vulnerability #2: Stored XSS Attack

  GIF: 
  
       Link Part 1: https://github.com/oleksandrbi/CodePathWeek8/blob/master/GreenXSSPART1.gif
       
       Link Part 2: https://github.com/oleksandrbi/CodePathWeek8/blob/master/GreenXSSPart2.gif
       
  COMMENTS:
  
    The Blue site has an 
  
## Red

Vulnerability #1: IDOR Attack
  
  GIF:
  
      Link: https://github.com/oleksandrbi/CodePathWeek8/blob/master/RedIDOR.gif
      
  COMMENTS:
  
 Vulnerability #2: CSRF Attack
 
  GIF:
  
      Link Part 1: https://github.com/oleksandrbi/CodePathWeek8/blob/master/RedCSRFPart1.gif
      
      Link Part 2: https://github.com/oleksandrbi/CodePathWeek8/blob/master/RedCSRFPart2.gif
      
  COMMENTS:


## Notes

Describe any challenges encountered while doing the work

