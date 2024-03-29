---
title: Clubforce Modernisation
subtitle: The future of sports club automation, payments, fundraising and communications.
date: 2022-01-08 00:00:00
description: I was lead designer on the new version of Clubforce, focused on improving the experience of thousands of users.
featured_image: clubforce02.png
gallery_images:
  - clubforce01.png
---

Clubforce is a sports club management platform. They provide memberships, fundraising, communications and promotion tools for over 2000 clubs across 35 countries. They are a market leader, with over 10 years history. Built for volunteers, by volunteers.

I joined the company as First Designer, to work on the next generation of the platform: Clubforce Modernisation (or simply "CM"). During my time there, I was involved on Everything Design: from collaborating with managers on user stories and backlog refinement, to building and presenting prototypes to different stakeholders, to developer hand-off.

### Qualitative User Research

The most important Clubforce offer is probably Fundraising. It's one of the reasons the company exists: to allow for people living abroad (the "Irish Diaspora") to be able to support financially their local clubs back at home.

One way clubs use to raise funds is by selling lotto tickets. In order to do that, they need to go through a multi-step process: validating licence details, connecting to a payment provider (Stripe), setting up recurring draws etc. It's not super complicated, but let's say things can go wrong.

To help better inform our decisions while building and iterating on those journeys, we did User Interviews. Our Customer Care team reached out to some folks (Clubforce users) and organised online sessions. Those were recorded, processed and the insights were used by the team to help prioritise stories.

Here's how one of those looked like (names were changed to protect their identities):

{% include post-components/gallery.html
  columns = 1
  full_width = true
  images = "/images/projects/clubforce05.png"
%}


### A design system?

The first version of the (web) platform had been built by a small group of full-stack engineers, without a dedicated designer. It was in pretty good shape, but two great challenges had to be addressed:

1. it had to scale
2. re-branding: we had to consider how to integrate a new logo, typography and colour scheme

I reached out to the engineers, to try and understand some of the decisions that had been made. We found out the interface was made of equal parts Material Design (Angular Material, specifically), Bootstrap and custom-built components.

{% include post-components/gallery.html
  columns = 1
  full_width = true
  images = "/images/projects/clubforce04.png"
%}

*Inventory of buttons in admin areas. And then the button component (on Figma)*

Following the Atomic Design principles, a Figma Library was the first thing we delivered. It contained documentation and guidelines for every component, from Typography and Colours, to page layouts.

The library is a living document. Any time a element needs to be introduced or existing elements need to be modified, we do inventory and consider the general impact. Developers and managers are included in the process, which allows for a more realistic cycle.

### Tokens for better website customisation

Club Websites are an important part of Clubforce Modernisation. An easy way for clubs to get closer to their supporters: posting news & updates, contact details and information, and a shop front for fundraising and memberships.

Customisation is a big part of this. Clubs want their websites to look & feel unique. Colours are one of the most recognisable aspects of a club identity.

We researched the most popular colours for each county in Ireland and used that as a starting point. We offer two options: one primary and one secondary. CSS variables are updated based on the user choices.

{% include post-components/gallery.html
  columns = 1
  full_width = true
  images = "/images/projects/clubforce03.png"
%}

*Exploring different colour combinations. A club from Co. Galway could select Maroon and Black as Primary and Secondary colours, whereas a club from Co. Mayo could pick Red and Green*

### Progressing the company's UX maturity level

I worked with the Head of Product on an initiative to progress the company UX Maturity Level, which at the time was at a low, emergent level. Our main focus was on increasing awareness and improving processes.

That was an ongoing effort. In practical terms it meant things such as:

- dedicated Slack channels and Confluence spaces for design-focused discussions, which were open to everyone in the company;
- a design blog, with regular status updates on ongoing projects and other long form articles;
- a series of talks and workshops on design concepts and process. Those happened in the office and were open to everyone in the company
