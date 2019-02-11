---
title: "Scenario Overview"
date: 2019-02-10T19:28:22-05:00
draft: true
weight: 211
---

### Architecture Diagram

On the Diagram below we start from moment A, where the monolithic application Pet Store has a functionality called ‘Veterinarian Management’,(Vets). The objective is to improve the Vets functionality without having to change the Monolithic application.

![Moment A](/images/monolith-to-micro/mom-a.png)

In order to achieve that, Gloo, the Hybrid Application Gateway, will be instructed to route requests to the Vets functionality of the application to a set of Microservices Called Vets v2. As a result of that, users will no longer rely on the Vets functionality from Pet Store. 

![Moment B](/images/monolith-to-micro/mom-b.png)