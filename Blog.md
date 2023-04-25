Blog Article: Coupling and Cohesion Issues in a Zombie Game Project

Purpose:

The purpose of this article is to identify and explain the issues of coupling and cohesion in a Python-based Zombie Game project found on a public GitHub repository. The article will also propose a plan to redesign and refactor the code to improve its coupling and cohesion.


Introduction:

The "Zombie Game" is a Python-based project that provides a fun and exciting gaming experience. It is a simulation of a zombie invasion and requires the player to survive the zombie attacks and complete objectives across multiple levels, each with increasing difficulty. The player has access to a range of weapons that they can use to defend themselves against the zombie horde. The game involves moving around a maze-like environment and attacking zombies, making it an engaging and thrilling adventure for players of all ages.

The GitHub repository for this project can be found at https://github.com/ndleah/python-mini-project/tree/main/Zombie_Game. At the time of analyzing this code, the latest commit SHA1 hash was afe4a3609a319526a0aaa989ae1e7c35626a8b86.

Coupling and Cohesion

Coupling and cohesion are fundamental concepts in software engineering that determine the quality and maintainability of a software system. Coupling refers to the level of interdependence between different modules within a software system, while cohesion refers to the degree to which the elements within a module are related to each other.

High coupling can result in a software system that is difficult to understand, modify, and extend, since changes to one module can have unintended effects on other modules. On the other hand, low cohesion can also make a software system hard to maintain, since modules with low cohesion tend to do too many things, making it challenging to isolate and fix bugs or add new features. It is essential to strike a balance between coupling and cohesion to ensure a software system is maintainable, scalable, and easy to comprehend.
