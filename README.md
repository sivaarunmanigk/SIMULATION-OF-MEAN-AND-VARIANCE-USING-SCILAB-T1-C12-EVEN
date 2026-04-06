# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN
AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

#EQUIPMENTS NEEDED:

.Computer with i3 Processor

.SCI LAB

ALGORITHM:

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x)=sin(x) or any other function.
Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
Evaluate the Function: Compute the function values at each of these sample points.
Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
Display Results: Output the computed mean variance and Cross Correlation

PROCEDURE:

1.Refer Algorithms and write code for the experiment.

2.Open SCILAB in System

3.Type your code in New Editor

4.Save the file

5.Execute the code If any Error, correct it in code and execute again

6.Verify the generated results

PROGRAM:

    clc;
    clear;
    close;
    
    // Step 1: Define signals
    x = [1 2 3 4 5];
    y = [5 4 3 2 1];
    
    // Step 2: Mean
    mean_x = mean(x);
    
    // Step 3: Variance
    var_x = variance(x);
    
    // Step 4: Cross-correlation
    corr_xy = xcorr(x, y);
    
    // Display results
    disp("Mean of x = ");
    disp(mean_x);
    
    disp("Variance of x = ");
    disp(var_x);
    
    disp("Cross-correlation of x and y = ");
    disp(corr_xy);
    
    // -------- PLOTTING --------
    subplot(3,1,1);
    plot(x);
    title("Signal x(n)");
    
    subplot(3,1,2);
    plot(y);
    title("Signal y(n)");
    
    subplot(3,1,3);
    plot(corr_xy);
    title("Cross-Correlation x(n) and y(n)");
![20260406_180145](https://github.com/user-attachments/assets/6dcb20f5-8656-4637-a85b-14a2f0c986e7)

RESULT:
![20260406_180150](https://github.com/user-attachments/assets/8cc28edc-3534-4394-a9f2-cd470ead7d72)
