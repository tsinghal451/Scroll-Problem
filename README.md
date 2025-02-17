# Issue with GSAP ScrollTrigger & Footer Overlapping

## Description
I'm facing an issue with GSAP ScrollTrigger in my project. I have an animation where the text inside `.unique-mask h2` scales up as I scroll. It works fine when scrolling with the scrollbar, but when using a trackpad, it behaves weirdly.

## What I Tried
- Setting `pinSpacing: false` in ScrollTrigger.
- Reducing `scale` value.
- Ensuring `overflow-x: hidden` in CSS.
- Adjusting `end: "+=1500"` to a smaller value.

## Screenshot
Below is a screenshot of the issue:

![GSAP Scroll Issue](Screenshot-2025-02-17-105543.png)

Let me know if you have any suggestions to fix this!

Thanks!
