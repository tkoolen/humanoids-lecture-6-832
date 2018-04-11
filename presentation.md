---
title: Group meeting April 4, 2018
theme: serif
highlightTheme: github
css: style.css
revealOptions:
    transition: 'fade'
    center: false
    slideNumber: true
---

<!-- ## More efficient autodiff for rigid body kinematics/dynamics -->

## Presentation title


---

### Basics

Foo:

* bar
* baz

---

### Fragments

* foo
* bar <!-- .element: class="fragment" -->
* baz <!-- .element: class="fragment" -->

---

### Fragments, part 2

* foo <!-- .element: class="fragment" data-fragment-index="2" -->
* bar <!-- .element: class="fragment" data-fragment-index="1" -->

baz <!-- .element: class="fragment" data-fragment-index="2" -->

---

### Code

'Dual number' type:

```julia
struct Dual
    val::Float64
    der::Float64
end
```

Inline code: `foo = bar`

---

### Math

Let

$$
c = \frac{\sum_i m_i H^w_i c_i}{\sum_i m_i}
$$

---

### Images 1

Using Markdown:

![branching](figures/branching.png "Branching")

---

### Images 2

Using HTML (allows for more options):

<center>
<img src="figures/branching.png" alt="branching" style="height: 200px;"/>
</center>

---

### More HTML

<center>
Center.
</center>

---

### Video

 <video width="320" height="240" autoplay>
  <source src="https://www.w3schools.com/html/movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video> 
