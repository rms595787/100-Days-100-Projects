# 🚀 Project 53

> Creating interactive spotlight effects using CSS variables and mouse movement.  
> Built as part of my 100 Projects Challenge.

---

## 🎥 Demo Video

🔗 Watch here:
[Video](./demo/Project%2053.mov)  
<video src="./demo/Project 53.mov" controls width="800"></video>

---

## 🧠 What I Learned

This project introduced me to **CSS custom properties (variables)**.

Example:

```id="yks5ib"
clip-path: circle(200px at var(--1) var(--2))
```

These variables can be dynamically updated using JavaScript.

Using the `mousemove` event, I updated the variable positions in real time:

```id="2k5t1y"
pos.style.setProperty('--1', e.clientX+"px")
pos.style.setProperty('--2', e.clientY+"px")
```

The result is a **spotlight effect that follows the cursor**, creating an immersive interaction.

This technique is extremely useful for building:

- reveal animations
- spotlight effects
- interactive landing pages

---

## 🔗 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)]([LinkedIn Profile](https://www.linkedin.com/in/rahul-sharma-94960a248/))

---

---

## 📢 LinkedIn Post

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)]([Post Link](https://www.linkedin.com/feed/update/urn:li:activity:7434092659713118208/?originTrackingId=FJn1v2khMgr0ZvCaV4xfUg%3D%3D))

---

⭐ If you found this helpful, consider giving it a star!

---
