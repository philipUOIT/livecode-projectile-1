# `livecode-projectile`
---
![](https://travis-ci.org/philipUOIT/livecode-projectile-1.svg?branch=master)

A simple implementation of an Euler integrator for projectile motion. This program was written (mostly) live, in lecture for SOFE-2850U in Fall 2017.

Next week, we will add drag and stopping conditions. The drag will make the output more interesting. Implementing stopping conditions in a generic way force us to introduce lambdas and templates.

## Compilation

Compile with
```bash
clang++ -std=c++14 -o projectile projectile.cpp
```
or
```bash
g++ -std=c++14 -o projectile projectile.cpp
```
and run as
```bash
./projectile
```
and watch your terminal fill with numbers.

## Output

The output will be 3 numbers that correspond to the position.
```
 x-position [m], y-position [m], z-position [m]
```
Plot them and you get the familiar parabolic trajectory, which will depend on your constants:  
![](plot.png)
