java c
Comp 330 (Fall 2024): Assignment 1 (version 0)
Answers must be submitted online by September 30 (11:59 pm), 2024.
General instructions
• Important: All of the work you submit must be done by only you, and your work must not be submitted by someone else. Plagiarism is academic fraud and is taken very seriously.
• To some extent, collaborations are allowed. These collaborations should not go as far as sharing code or giving away the answer.  You must indicate on your assignments the names of the people with whom you collaborated or discussed your assignments (including members of the course staff). If you did not collaborate with anyone, write “No collaborators”. If asked, you should be able to orally explain your solution to a member of the course staff.
• It is your responsibility to guarantee that your assignment is submitted on time. We do not cover technical issues or unexpected difﬁculties you may encounter. Last minute submissions are at your own risk.
• Multiple submissions are allowed before the deadline. We will only grade the last submitted ﬁle. Therefore, we encourage you to submit as early as possible a preliminary version of your solution to avoid any last minute issue.
• Late submissions can be submitted for 24 hours after the deadline, and will receive a ﬂat penalty of 20%. We will not accept any submission more than 24 hours after the deadline. The submission site will be closed, and there will be no exceptions, except medical.
• In exceptional circumstances, we can grant a small extension of the deadline (e.g. 24h) for medical reasons only. However, such request must be submitted before the deadline, justiﬁed and approved
by the instructors.
• Violation of any of the rules above may result in penalties or even absence of grading. If anything is unclear, it is up to you to clarify it by asking either directly the course staff during ofﬁce hours, by email at or on the discussion board on Ed.  Please, note that we reserve the right to make speciﬁc/targeted announcements affecting/extending these rules in class and/or on the website.  It is your responsibility to monitor Ed for announc代 写Comp 330 (Fall 2024): Assignment 1Matlab
代做程序编程语言ements.
• The course staff will answer questions about the assignment during ofﬁce hours or in the online forum. We urge you to ask your questions as early as possible. We cannot guarantee that questions asked less than 24h before the submission deadline will be answered in time. In particular, we will not answer individual emails about the assignment that are sent the day of the deadline.
• Unless speciﬁed, you must show your work and all answers must be justiﬁed.


1.  (10 points)  Let Σ = {0, 1}. Draw a deterministic ﬁnite automaton (DFA) that accepts the language 
L1  = {w|w has an even number of letters, and
w does not have two identical consecutive letters}
Hint:  You can build a automaton for each language (i.e., “even number of letter” and “no two identical consecutive letters) then construct the product of the two’s.
2.   (a)  (10 points)  Convert the following nondeterministic ﬁnite automaton (NFA) into a DFA. ∈

(b)  (5 points)  Use your solution to build another DFA that accepts the complementary language L = { w | w  L }
3.  Write a regular expression describing the set of strings over the alphabet Σ = {0, 1} that:
(a)  (10 points)  Does not contain the string 110.    (b)  (10 points)  Start and end with the same letter.
4.  Let Σ = {0, 1}. Show that:
(a)  (10 points)  the language L2  = { 0ks0k   j k ≥ 1 and s ∈ Σ*  } is regular.
(b)  (10 points)  the language L3  = { 0k 1s0k   j k ≥ 1 and s ∈ Σ*  } is not regular.
5.  We introduce the rotation operation on languages rot(L) = {xy j yx ∈ L }.
(a)  (10 points)  Show that rot(L) = rot(rot(L))). Start to show that rot(L) ≤ rot(rot(L)). Then, show rot(L) ≥ rot(rot(L)).
(b)  (15 points)  Show that a regular language L is closed under the operation rot().  Let ML  be a DFA that recognizes L. Show how to build a NFA NL  that recognizes rot(L).
6.  (10 points)  Using the k-path induction method, write a regular expression representing the language accepted by the following DFA. Show your work.  Simplify the regular expression as much as you can.








         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
