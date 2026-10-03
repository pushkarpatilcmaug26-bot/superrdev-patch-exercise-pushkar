I reviewed the task tracker across the frontend, backend, and database layers and fixed the highest-value issues identified during the exercise.

Fixed the task loading/error state in frontend/src/hooks/useTasks.js. The loading state is now reset for both successful and failed API requests, and previous errors are cleared when a new request starts.
Fixed [BUG 1 — Status filter is incorrect].
Fixed [BUG 2 — When I select "IN PROGRESS" in the status filter so "DONE" & "OPEN" is also coming there].

The changes were kept focused and did not involve rewriting the application.

What I Chose Not to Change

I did not change issues that were lower priority, outside the main task flow, or that would require a larger refactor. The goal was to make a small, targeted patch within the exercise timebox while avoiding unnecessary changes.

Tools / AI Used

I used ChatGPT to help inspect the code, understand the existing implementation, identify potential bugs, and discuss possible fixes. I reviewed the suggested changes myself, applied only focused changes, and tested the application locally before committing them.
