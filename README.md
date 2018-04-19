# Week-8-WS



Time spent: 5 hours spent in total

Objective: This week I will have to Identify vulnerabilities in three different versions of the Globitek website: Blue, Green, and Red.

These are all the six possible exploits that were apart of this week challenge:

Username Enumeration:

Insecure Direct Object Reference (IDOR):

SQL Injection (SQLi):

Cross-Site Scripting (XSS):

Cross-Site Request Forgery (CSRF):

Session Hijacking/Fixation:

The different version on this site has been given two of the six vulnerabilities as shown.

Blue
Vulnerability #1: SQL Injection (SQLi)
Here I will be running ' OR SLEEP(5)=0--' as the ID will set the blue link to sleep for 5 seconds accordingly. And this is as follow:

Vulnerability #2: Session Hijacking/Fixation
Here I'm using session ID and using it as session ID for a new browser that is not logged in worked on blue link. And its called Session Hijacking/Fixation

Green
Vulnerability #1: Username Enumeration
The approach I used on this green link, it is easy to figure out if the user exist. If bold and it means the account exists. If it is not bold and it means the account doesn't exist. Username Enumeration

Vulnerability #2: Cross-Site Scripting (XSS)
Here is the posting <script>alert('Stephen found the XSS!');</script> will give an XSS when the admin views the feedbacks: XSS

Red
Vulnerability #1: Insecure Direct Object Reference (IDOR)
In this part of the assignment the red link, you can change ID number and see people you normally wouldn't bev allowed to see. IDOR Vulnerability #2: Cross-Site Request Forgery (CSRF)
The good news I think about running a HTML form on this assignment, is that the values can be changed without having the proper access or even being an admin. The HTML is in this repo accordingly. IDOR



