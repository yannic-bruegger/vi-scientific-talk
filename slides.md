---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# persist drawings in exports and build
drawings:
  persist: false
---

# Communicating Visualizations without Visuals
<!--
Communicating Visualizations without Visuals: Investigation of Visualization Alternative Text for People with Visual Impairments

Accessible Visualization via Natural Language Descriptions: A Four-Level Model of Semantic content
-->
Investigation of Visualization Alternative Text for People with Visual Impairments

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: two-cols
---

# Selection

- IEEE VIS: Visualization & Visual Analytics 2021
- Thursday, 28<sup>th</sup> October
- Accessible Visualization and Natural Language
- **Communicating Visualizations without Visuals**: Investigation of Visualization Alternative Text for People with Visual Impairments
- **Accessible Visualization via Natural Language Descriptions**: A Four-Level Model of Semantic content

::right::

<img alt="Cover page of first paper" src="/images/papers.png" class="center">
<footer class="text-xs absolute bottom-0px pb-4">
Source: http://ieeevis.org/year/2021/info/papers-sessions
</footer>
---
layout: two-cols
---

# Take a look at ...

<img alt="Cover page of second paper" src="/images/paper2.png" class="pr-10px">

::right::


# ... and compare it to ...

<img alt="Cover page of first paper" src="/images/paper1.png" class="pl-10px">

---

# Context: Accessibility on the Web

- Accessibility is the practice of making your websites usable by as many people as possible.
  - people with impairments
  - small screens (i.e. mobile)
  - slow internet connection

<br>

> **Accessibility is the right thing to do.** Providing accessible sites is part of the law in some countries, which can open up some significant markets that otherwise would not be able to use your services or buy your products.

<footer class="text-xs absolute bottom-0px pb-4">
Source: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility
</footer>

<!--
- Test12
-->

---

# Context: People with Visual Impairments

- Semantic HTML

---
layout: center
---

# Learn More

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
