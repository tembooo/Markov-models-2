# Markov-models-2
First-Order Markov Model 
![image](https://github.com/user-attachments/assets/43ce92f3-c6c0-499f-a4af-4741f7b330cd)
Let us assume a first-order Markov model where the states Si correspond with letters of English language words.

### Instructions

1. Implement a function for estimating the initial state probabilities  
   πi ≡ P(q1 = Si)  
   and the transition probabilities  
   aij = P(qt+1 = Sj | qt = Si)

2. Preprocess the given text as needed for the estimation and use it for testing the implementation.

3. Submit the estimates as:
   - a histogram for π
   - an intensity image for aij

### Additional Files

- `call_wild.txt`

### Hints

- The initial state probabilities are related to the **first letters of words**.
- The transition probabilities are related to what is **likely to come after a specific letter**.
