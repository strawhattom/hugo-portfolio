---
title: "Secure Web Dev"
date: 2022-10-01T00:00:00+02:00
draft: false
summary : "A web filming location CRUD app coded with SvelteKit and Express"
tags: ["sveltekit", "web app", "express", "rest api"]
categories: ["school project"]
author : "Tom XIE"
# cover:
#     image: "."
#     alt: "Preview"
---

This post is still in building !

**[Demo](https://tangerine-chaja-9ff120.netlify.app/)**

[Frontend source code](https://github.com/strawhattom/secure-web-dev-frontend)\
[Backend code](https://github.com/strawhattom/secure-web-dev-backend) \
[Docker version](https://github.com/strawhattom/docker-secure-web-dev/)

## Context
During my 7th & 8th semester (September 2022 - February 2023) we got introduced in web developement especially in a secured way by starting with a back-end, we based our back-end from a french open data [website](https://opendata.paris.fr/explore/dataset/lieux-de-tournage-a-paris/information/?disjunctive.type_tournage&disjunctive.nom_tournage&disjunctive.nom_realisateur&disjunctive.nom_producteur&disjunctive.ardt_lieu).

## Functionnalities implemented
- Login/register
- Different view for a specific role (admin/visitor)
- Register/Delete/Edit a location for an admin
- View locations' array
- Pagination
- JWT token to access to the database
- Unable to access to admin's feature as a visitor