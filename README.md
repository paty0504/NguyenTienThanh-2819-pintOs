# NguyenTienThanh-2819-pintOs
This repository contain code for my project in Operating System course  (SET, HUST) in 20212.

To make my teacher easier to track my work, i put some comment line /* My code begin */

For example:

/* My code begin */

...

the code i've changed or modified

//Some comment to explain

...

/* My code end */

This repo contains my solution for pintos' **Project 1 - Alarm clock** probelm and **Project 0**.
With Project 1, you can spot that further than just solving Alarm clock problems, i'm also dealing with the Priority Problems. **But my test case for that problems haven't pass yet**. So soon, i will finish that problem and the entire Pintos project.

To avoid some confuse: This is the list of my work with Alarm clock problem: 

 - in timer.c: modify timer_sleep() and timer_interrupt().
 - in thread.c: add new function: thread_sleep(), thread_foreach_sleep(), thread_less_priority() at the bottom of the file.
 - in thread.h: declare THREAD_SLEEP state, struct list sleep_list, int64_t sleep_tick.
 
 For further detail, view my REPORT (Vietnamese version).

With Project 0, follow the instruction from the pintos document, i only modify os0/caltrain.c (for CalTrain Problem) and os0/reaction.c (for Chemical Reaction Problem). In this Project, there is not much previous code that could be confused with my code, so i don't have to use the comment as mentioned above.

This project could not be completed without the support (from the lectures at my university) of my teacher, Dr.Pham Van Tien (SET,HUST) and the pintos document: https://web.stanford.edu/class/cs140/projects/pintos/
