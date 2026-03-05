# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

First the difficulty and attempts were messed up. Just based on my intuition the harder mode should have less attempts for a wider range and the easier mode should have more attempts for a smaller range. But on my first run, the easy mode only had 6 attempts where normal had 8 and hard 4 and the range for easy was 20, medium 100, and hard 50. 

Second, the guessing mechanism didn't work at all, I tried to enter a number then press enter, as it prompted me, and it did nothing not even increment guesses. 

--- 

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

I kept Claude code in the loop by giving it context of what it fixed and what still needed changes.
A time it was wrong was when it kept the ranges for easy medium and hard different when they should be all 1-100 and only differing by number of attempts allowed. 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

I just tested it on the local host to see if the bug was fixed alot of it wasn't too hard to manually test to see if it was fixed 
---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

I honestly didn't notice the secret number kept changing I first started off telling cluade to scan and see what bugs it could find and fix itself and I guess this was one of them. 
---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

- Being able to understand the logic issues beforehand yourself and a potential solution so you save time and can have claude work on more extensive issues and not get caught up on tight easy to understand corners if you take time to understand the code before offshoring the work to AI. 
