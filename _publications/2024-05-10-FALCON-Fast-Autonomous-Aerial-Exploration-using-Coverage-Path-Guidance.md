---
title: "FALCON: Fast Autonomous Aerial Exploration using Coverage Path Guidance"
collection: publications
permalink: /publication/FALCON-Fast-Autonomous-Aerial-Exploration-using-Coverage-Path-Guidance  	
excerpt: '**Yichen Zhang**\*, Xinyi Chen\*, Chen Feng, Boyu Zhou, Shaojie Shen'
date: 2024-05-10
venue: 'IEEE Transactions on Robotics (Conditionally accepted)'
paperurl: 
citation: 
---

Conditionally accepted as Regular	

This paper introduces FALCON, a novel Fast Autonomous expLoration framework using COverage path guidaNce, which aims at setting a new performance benchmark in the field of autonomous aerial exploration. Despite recent advancements in the domain, existing exploration planners often suffer from inefficiencies such as frequent revisitations of previously explored regions. FALCON effectively harnesses the full potential of online generated coverage paths in enhancing exploration efficiency. The framework begins with an incremental connectivity-aware space decomposition and connectivity graph construction, which facilitate efficient coverage path planning. Subsequently, a hierarchical planner generates a coverage path spanning the entire unexplored space, serving as a global guidance. Then, a local planner optimizes the frontier visitation order, minimizing traversal time while consciously incorporating the intention of the global guidance. Finally, minimum-time smooth and safe trajectories are produced to visit the frontier viewpoints. For fair and comprehensive benchmark experiments, we introduce a lightweight exploration planner evaluation environment that allows for comparing exploration planners across a variety of testing scenarios using an identical quadrotor simulator. Additionally, a VECO criteria is proposed for an in-depth analysis of FALCON's significant performance in comparison with the state-of-the-art exploration planners. Extensive ablation studies demonstrate the effectiveness of each component in the proposed framework. Real-world experiments conducted fully onboard further validate FALCON's practical capability in complex and challenging environments. The source code of both the exploration planner FALCON and the exploration planner evaluation environment will be released to benefit the community.

<iframe width="560" height="315" src="https://www.youtube.com/embed/BGH5T2kPbWw?si=YzrRhuvMmnMUnVJW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[Download paper here](https://arxiv.org/pdf/2407.00577)

Recommended citation: Y. Zhang\*, X. Chen\*, C. Feng, B. Zhou, and S. Shen, ‘APACE: Agile and Perception-Aware Trajectory Generation for Quadrotor Flights’, arXiv preprint arXiv:2407. 00577, 2024.
