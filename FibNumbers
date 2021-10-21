# Fib Numbers - Dynamic passrogramming
# Claire Holt

# Number of Fib numbers to find:
size = 100

# Initialize array:
S = [0]*size

# Set base cases:
S[0] = 0
S[1] = 1

# To find the next fib number, lookup the previous two in the array and add them together.
for i in range (2, size):
    S[i] = S[i-1] + S[i-2]
    
print(S)

# This approach allows us to avoid recomputing all previous Fib numbers to find the next number. Instead, we store each fib number in an array and lookup previous two Fib numbers to calculate next one. Array lookup is much faster than recursive call.


