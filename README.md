# OPTIMIZATION-MODEL

**COMPANY**: CODTECH IT SOLUTION

**NAME**: NIKITA JAYANAND WARE

**INTERN ID**: CT6WGZI

**DOMAIN**: DATA SCIENCE

**BATCH DURATION**: JANUARY 5th, 2025 to FEBRUARY 20th, 2025

**MENTOR NAME**: NEELA SANTHOSH KUMAR

**Problem Statement**:
A manufacturing company produces Product A and Product B and wants to maximize profit while considering resource constraints and labor hours.

Decision Variables:
x = Number of units of Product A
y = Number of units of Product B

Objective Function (Maximize Profit):
Maximize 
     𝑍=𝑝𝐴⋅𝑥+𝑝𝐵⋅𝑦
  Where:
𝑝𝐴= Profit per unit of Product A
𝑝𝐵= Profit per unit of Product B

Constraints:
Resource Constraint: 2x+y≤1000
Labor Hour Constraint: 3x+2y≤600
Non-negativity Constraints: x,y≥0

Solution Approach
Use Linear Programming (LP) and solve the optimization problem using PuLP (Python LP solver). The solver provides an optimal production plan that maximizes profit while satisfying constraints.

Visualizations
1️⃣ Feasible Region Plot
The feasible region is the shaded area in the graph below, representing all possible values of 𝑥 and y that satisfy the constraints.
The blue line represents 2x+y≤1000
The orange line represents  3𝑥+2𝑦≤600
The shaded region is the feasible area where both constraints hold.
2️⃣ Optimal Production Plan
The optimal solution suggests:

Produce 300 units of Product A
Produce 200 units of Product B

Product A (Orange Bar): 300 units
Product B (Blue Bar): 200 units
These values maximize profit while adhering to constraints.
