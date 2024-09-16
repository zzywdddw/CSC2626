### Week 2: Introduction to Optimal Control & Model-Based RL
## LEC 02; 2024.9.19; Monday  

Linear Quadratic Regulator(LQR)  
X<sub>t+1</sub>=Ax<sub>t</sub> + Bu<sub>t</sub>  
X -> state; U -> Control, command, action applied to the system  

Application: ![image](https://github.com/user-attachments/assets/2f02f1f5-41a2-4ed2-8c9b-50b3ddfa16a3)  
The goal of LQR is :
• Stabilize the system around state X<sub>t</sub> = 0 with control U<sub>t</sub> = 0  
• Then and the system will remain at zero forever  

Advantages:
• If system is linear LQR gives the optimal controller that takes the system’s
state to 0 (or the desired target state, same thing)
Drawbacks:
• Linear dynamics
• How can you include obstacles or constraints in the specification?
• Not easy to put bounds on control values 
