# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Yazeed Osama Binsulih] |
| **Student ID** | [445050301] |
| **University Email** | [445050301]@std.psau.edu.sa |
| **GitHub Username** | [yazid998] |
| **Repository Link** |  https://github.com/yazid9988/OS-Assignment1-Yazeed-Binsulih  |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1IcWl_DIDoV2LO2rDFqb78fb6uk7IsO8e/view?usp=drive_link

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [2-10-2026]
**What I did**: Added my student ID to the code.

**Details**: Inserted my university ID into the ⁠main⁠ method and set up the random number generation logic as required.

**Challenges**: Needed to ensure the ID was correctly formatted within the output strings to match the assignment specifications.

**Solution**: Verified the syntax and tested the initial output to ensure the ID printed cleanly to the console.


**Time spent**: 35 minutes 
---

### Entry 2 - [6-10-2026]
**What I did**: Set up the development environment.

**Details**: Installed VS Code and configured the Java ecosystem, ensuring the compiler and runtime were properly linked.

**Challenges**: Encountered path configuration issues where the terminal could not locate the Java Development Kit tools.

**Solution**: Downloaded JDK 17, updated the system environment PATH variables, and restarted the IDE.

**Time spent**: 45 minutes 

---

### Entry 3 - [7-10-2026]
**What I did**: Implemented Feature 1 (Add Priority).

**Details**: Modified the ⁠Process⁠ class to include a priority attribute and updated the insertion logic to place processes in the Ready Queue based on this value.

**Challenges**: Sorting the queue dynamically while maintaining the chronological order for processes with identical priority levels.

**Solution**: Utilized a custom comparator that checks priority first, falling back to arrival sequence for ties.

**Time spent**: 50 minutes 

---

### Entry 4 - [07-10-2026]
**What I did**: Implemented Feature 2 (Count and display total context switches).

**Details**: Introduced a static counter variable in the scheduler to track every time the processor switches execution between different processes.

**Challenges**: Ensuring the counter only increments during actual context switches and not when a process continues its own execution slice.

**Solution**: Placed the counter increment logic specifically within the process yielding and scheduling rotation methods.

**Time spent**: 1 hour 

---

### Entry 5 - [8-10-2026]
**What I did**: Completed Feature 3 implementation.

**Details**: Finalised the waiting time and turnaround time tracking mechanisms for all processes and structured the final summary output table.

**Challenges**: Formatting the floating-point averages to display exactly two decimal places in the terminal.

**Solution**: Used the ⁠String.format()⁠ method with ⁠%.2fms⁠ padding to standardize the output.

**Time spent**: 1 hour 30 minutes 

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned how to use multithreading in Java using the ⁠Runnable⁠ interface. I used ⁠Thread.start()⁠ to run processes at the same time. I also used ⁠Thread.sleep()⁠ to simulate CPU execution time. Using ⁠Thread.join()⁠ helped me wait for threads to finish their work properly. I was surprised by how fast threads process tasks concurrently. Overall, this assignment made the OS concepts very clear to me.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part was tracking the waiting time and turnaround time in Feature 3. It was hard to update the variables correctly when a process was re-queued. I struggled to separate the actual waiting time from the execution time. Adding priority levels from 1 to 10 also made the logic more complex. I had to review my calculations multiple times to make sure they were right. Testing the scheduler step-by-step helped me solve this issue.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame my challenges by testing my code step-by-step. I added ⁠System.out.println⁠ statements to print and track process states in the console. Reading the ⁠README.md⁠ file again helped me understand the exact requirements. I tested my changes after writing every small part of the code. Checking the console output regularly showed me where the logic failed. This trial-and-error approach helped me fix all the bugs.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in many everyday applications like web browsers and music players. In a music player, one thread plays audio while another thread updates the user interface. Web browsers use separate threads for each tab so one tab does not freeze the rest. Mobile apps use background threads to download data without stopping the screen. The Round-Robin scheduling we built works just like real operating system schedulers. Understanding these concepts helps in writing fast and responsive software.]

### Optional: What would you like to learn more about?

[Confident. I have a solid understanding of how tasks are distributed among threads and how this effectively accelerates the overall process execution. However, I recognize the need for further practice to master complex synchronization scenarios.]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Feedback on the assignment: The assignment was highly beneficial as it bridged the gap between theoretical concepts of process management and quantum time, and their practical implementation in code. It was a genuinely enjoyable and rewarding experience.]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is an independent execution environment with its own isolated memory space, whereas threads within the same process share the same memory heap. In our code, the class named ⁠Process⁠ represents a simulated process model, but it is actually executed using a real Java ⁠Thread⁠ object. We used threads instead of separate processes because thread creation has much lower overhead and allows faster communication through shared memory. Specifically, this is implemented in ⁠SchedulerSimulation.java⁠ where we invoke ⁠new Thread(process)⁠ inside the ⁠addProcessToQueue()⁠ method.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process does not finish within its time quantum, the CPU scheduler interrupts it, calculates its remaining time, and re-queues it back into the ready queue. For example, in my program output where the time quantum is 3000ms, process P1 had a burst time of 6767ms, which exceeded the quantum limit. After completing its first 3000ms, it was preempted and added back to the ready queue with a remaining time of 3767ms. This re-queueing mechanism ensures fairness by allowing other processes to execute before P1 gets another turn.]

Example from my output:
```
[P1 completed quantum 3000ms | Remaining time: 3767ms
+ P1(priority: 9) added to ready queue | Burst time: 6767ms
]
```

**Explanation of example:**
[Because the burst time of process P1 (6767ms) was greater than the 3000ms time quantum, it could not finish in a single run. Therefore, the scheduler interrupted P1 after its quantum expired, performed a context switch, and re-queued it into the ready queue to finish its remaining execution time in the next cycle.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 enters the New state right after the ⁠Process⁠ object is instantiated using its constructor before its thread is launched.]

2. **Runnable**: [P1 becomes Runnable when the scheduler invokes ⁠thread.start()⁠ inside ⁠addProcessToQueue()⁠, making it ready for CPU execution.]

3. **Running**: [P1 is in the Running state when the CPU scheduler allocates a time quantum to it, executing its task inside the ⁠run()⁠ method.]

4. **Waiting**: [P1's thread enters a Waiting/Sleeping state when it calls ⁠Thread.sleep()⁠ to simulate the time quantum or context switching delay.]

5. **Terminated**: [P1 enters the Terminated state after its remaining burst time reaches zero and its ⁠run()⁠ method finishes execution completely.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[Operating systems use Round-Robin scheduling to manage multiple running applications and system tasks on a single CPU core.]

**Why Round-Robin works well here**:
[It guarantees absolute fairness and responsiveness by giving every application an equal time slice (quantum) so that no single task blocks the entire system. In this scenario, running applications act as the "processes", the OS preemption timer acts as the "time quantum", and the CPU core register saving acts as the "context switch".]

### Example 2: [Name of application/scenario]

**Description**:
[Modern web browsers use multithreading and scheduling algorithms to manage multiple open tabs simultaneously.]

**Why Round-Robin works well here**:
[It ensures predictability and responsiveness so that a heavy script running in one tab does not freeze the user interface of other tabs. Here, each browser tab acts as a "process/thread", the responsive event loop slice acts as the "time quantum", and switching between active tab views acts as the "context switch".]

## Summary

**Key concepts I understood through these questions:**
1. The fundamental architectural differences in memory sharing and creation overhead between threads and processes.
2. How the Round-Robin queue mechanism handles preemption and re-queuing to maintain fairness.
3. The precise state transitions a thread goes through during its lifecycle from creation to termination.

**Concepts I need to study more:**
1. Advanced thread synchronization and mutual exclusion locks.
2. Complex multi-core CPU scheduling algorithms.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
