# Waypoints patroling tutorial
This shows how to make an AI patrol between way points

## 1. Create a new scene

Start by creating a new scene called `AIPatroling`.

Add a plane called `Floor`, a 3D Cube named `Enemy` and a 3D very small Cube named `WayPoint`.

Duplicate the small 3D Cube, this wil give us three `WayPoints`.

Make three new materials and asing a different colour for each one. Add a different color to the `Floor`, `Enemy` and `Waypoints`.

## 2. Create the  

Create a new folder called Scripts and create a new script called `EnemyAI`.

We are going to make our enemy patrol between specific waypoints, in any order we want, and a speed public variable so we can choose how fast we want the enemy to patrol around. To make this we will need a `public Transform` which means wherever the waypoints are, a `public int` for the speed so we can change it in inside Unity. We will also make a `float dist` to check the distance between our AI and the current waypoint.







Creating a waypointIndex will show us an array in the inspector where we will drag 
