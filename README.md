# OR Gate — Neural Network in C

A single neuron trained to learn the OR gate using gradient descent, written in plain C.

## Build
gcc gates.c -o gates -lm

## Run
./gates

## What it does
- Sigmoid activation
- MSE cost function
- Finite difference gradient approximation
- Converges in ~100,000 iterations
