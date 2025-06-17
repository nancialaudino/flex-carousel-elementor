# Carousel Anything – Elementor Widget

## 🧭 Project Description

**Carousel Anything** is a custom WordPress plugin designed to work seamlessly with Elementor. It enables users to create responsive, customizable carousels optimized for mobile devices to enhance user experience (UX).

This project is developed in the context of a **professional immersion internship**, based on the specifications outlined in the official *Cahier des Charges*, ensuring flexibility, performance, and compatibility with modern development practices.

---

## ✨ Features (based on Cahier des Charges)

### 📦 Slides
- Each slide is an independent content block.
- Unlimited slides supported via **Elementor Repeater**.
- Each slide supports an image with custom height.

### 🖼 Slide Configuration (partially implemented)
- Image input with fixed height (600px by default).
- (To-do) Option to use either manual content or Elementor template.
- (To-do) Conditional rendering (hide empty fields).

### 🎨 Style Parameters (partially implemented)
- Image height enforced even inside Elementor editor.
- Tight spacing between slides for seamless layout.
- Autoplay enabled with smooth scrolling (`ease-in-out`).
- Navigation arrows styled as icons only.
- (To-do) Toggle options for arrows and dots.
- (To-do) Center mode for active slide alignment.

### 📱 Mobile UX
- Fully responsive layout.
- Smooth scrolling and swipe support on mobile.
- Infinite loop enabled with autoplay.

### ⚙️ Integration & Compatibility
- Fully compatible with **Elementor Website Builder**.
- Works with most WordPress themes.
- Lightweight, performant and secure.
- Slick Carousel loaded via CDN (no local overhead).

---

## ✅ Feature Checklist

| Feature                                                                 | Status       |
|------------------------------------------------------------------------|--------------|
| Elementor Repeater for multiple slides                                 | ✅ Done      |
| Image field per slide                                                  | ✅ Done      |
| Image height customizable (default: 600px)                             | ✅ Done      |
| Left/right navigation arrows (icons only)                              | ✅ Done      |
| Smooth scrolling, infinite autoplay                                    | ✅ Done      |
| Tight slide spacing (images appear side-by-side)                       | ✅ Done      |
| Functional in both Elementor editor and frontend                       | ✅ Done      |
| Slick Carousel initialized via CDN                                     | ✅ Done      |
| Option to choose between manual or template content                    | ❌ To-do     |
| Conditional rendering (skip empty fields)                              | ❌ To-do     |
| Option to toggle arrows visibility                                     | ❌ To-do     |
| Option to enable/disable navigation dots                               | ❌ To-do     |
| Center mode for active slide                                           | ❌ To-do     |
| Icon Box / Image Box style controls                                    | ❌ To-do     |
| Responsive visibility by device (desktop/tablet/mobile)                | ❌ To-do     |
| Full technical and user documentation                                  | ⚠️ In progress |

---

## 📁 Plugin Structure

```
carousel-anything/
├── carousel-anything.php                 # Plugin entry point
├── class-carousel-anything-widget.php   # Elementor widget definition
├── carousel-anything.js                 # Slick Carousel initialization
├── carousel-anything.css                # Styles for slides, arrows, and layout
```

---

## 📌 Next Steps

- [ ] Add Elementor template support for each slide
- [ ] Add toggle controls for arrows, dots, and center mode
- [ ] Conditionally hide empty slide fields
- [ ] Enable device-based visibility control
- [ ] Write full user and technical documentation

---

## 🤝 Contributions

Contributions are welcome. Please follow the technical and functional specifications outlined in the original *Cahier des Charges*.
