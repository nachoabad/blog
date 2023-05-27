---
layout: default
title:  "Boring Code"
---

# {{ page.title }}

Despite its bad reputation, boredom appears to me as a good state to be in: it’s free of stress and worries, and it can be a fertile ground to explore and innovate.

Coding, however, is supposed to be excting and fun, not boring. It is certainly fun when you are starting a side project or trying out a new technology. You keep adding lines of code to what once were blank files and a system that follows your instructions is born. Magical! 

If you keep advancing, adding more and more lines, a threshold is inevitably crossed. Fun suddenly starts being less predominant and other emotions mix in: doubt, confusion, impostor syndrome. In a professional environment, fun gets worn out even quicker when you are primarily measured by how good your code is and how fast you can deliver it.

Over my years as a software engineer I have distanced myself from the fun lines of code experience and I’ve begun to appreciate what I call Boring Code. Not the clever or particularly elegant one. But the one that is so straight-forward that, after reading it, you yawn. What you see throughout the code base is so repetitive, familiar, easy, that it’s boring.

Positively boring? Aren’t we supposed to be passionate about our craft?

It seems paradoxical. But the fun is still there, it just shifts. The scars by being held responsible for a large, legacy, multi-stack system, with rotating developers, become an antidote against the urge to have fun writing something particularly clever and elegant for people to review.

The fun is no longer, as an evident example, quickly hacking a JS snippet in the internal admin app to implement that cool drag & drop feature the marketing team keeps asking for. It shifts to figuring out if and how the current server side rendering implementation can fulfill the marketing team needs.

Boring code seems simple. Writing it consistently throughout the code base is a very hard task, similar to how highly skilled professionals make hard things look dead-simple to perform. It involves first of all, deciding whether writing code it’s at all necessary. It requires a vast understanding of the domain, a previous and continuous negotiation on styles, and a sharp creativity for naming and scoping things. None of that is explicitly visible on a Pull Request. One can get daunted by the urge to present (read, impress) elegant language idiomatics or introduce a clever pattern.

Boring Code is achieved by exercising of all those pragmatic, clean, intention-revealing, SOLID practices. The crystallization happens when you see the same things over and over: the exact same way you call external APIs. The exact same way to unit tests. The exact same way to catch and notify exceptions. “Oh that again… How boring”.
You don’t agree with something? Find or create the time and space for discussing it. Come prepared with examples and data to counter face other people strong arguments. Be open to disagree and commit. 
A big role is played by the “Convention over Configuration” philosophy.
Boring is the opposite of: going add a feature. It’s pretty similar to what A, B and C does. But each of those have different approaches. Which one should I take? Should I go with my own D?
The fun is out there, but it gradually moves from “what’s a clever way to write that concrete function or module”, to aiming to sustain a controlled, maintainable and expandable system.
The whole thing working seems majestic from afar, but when you approach it with a magnifying glass, you only discover a collection of boring small pieces, orchestrated.
Next time I write a piece of code, how can I make the reader understand so clear and fast what it does, makes it so familiar. that it seems boring
Repetitive == consistent
