# Quora-Question-Pairs

Quora is a website used by millions of people to gain and share knowledge. From asking questions, to writing answers, Quorans form a large community. Most of the times, when we want to gain some second opinion, or know about something, we usually end up going to Quora for answers.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term. (Credits: Kaggle)

#Problem Statement
- Identify if the questions asked on Quora are duplicate of the ones that have already been asked or not
- This could prove to be useful to instantly provide answers to questions that have already been answered.
- We are tasked with predicting whether a pair of questions are duplicates or not.

#Business Objectives and Constraints
- The cost of a mis-classification can be high.
- We would want a probability of a pair of questions to be duplicates so that we can choose any threshold of choice.
- No strict latency concerns.
- Interpretability is partially important.
