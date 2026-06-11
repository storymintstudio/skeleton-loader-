# 💀 Skeleton Loader UI

A pure CSS skeleton loader with shimmer animation — built in dark theme with 3 variants.

-----

## ✨ Live Preview

> Card Skeleton → List Skeleton → Profile Skeleton

All shimmer animations are CSS-only. Zero JavaScript.

-----

## 📦 Variants Included

|Variant             |Description                           |
|--------------------|--------------------------------------|
|**Card Skeleton**   |Thumbnail + text lines + avatar footer|
|**List Skeleton**   |Square thumb + 2 text lines per row   |
|**Profile Skeleton**|Avatar + bio + stats + button         |

-----

## 🛠️ Built With

- HTML5
- CSS3 (keyframe animation, linear-gradient shimmer)
- Google Fonts — Inter

-----

## 🎨 Design Tokens

```css
--bg:        #0a0a0a;
--card:      #111111;
--border:    #1f1f1f;
--skeleton:  #1a1a1a;
--shimmer:   #c8ff0022;  /* lime green subtle glow */
```

-----

## 🚀 How to Use

1. Clone or download this repository
1. Open `skeleton-loader.html` in your browser
1. Copy the `.skeleton` class and `@keyframes shimmer` into your own project
1. Adjust widths/heights to match your content layout

-----

## 🔑 Core CSS — Shimmer Effect

```css
@keyframes shimmer {
  0%   { background-position: -600px 0; }
  100% { background-position:  600px 0; }
}

.skeleton {
  background: #1a1a1a;
  background-image: linear-gradient(
    90deg,
    #1a1a1a 0px,
    #2a2a2a 40px,
    #c8ff0022 80px,
    #2a2a2a 120px,
    #1a1a1a 160px
  );
  background-size: 600px 100%;
  animation: shimmer 1.6s infinite linear;
  border-radius: 6px;
}
```

-----

## 📁 Folder Structure

```
skeleton-loader/
│
├── index.html       ← main file
└── README.md        ← you are here
```

-----

## 🤝 Credits

- First draft generated with **Claude AI**
- Customized & crafted by **Storymint Studio**

-----

## 📸 Follow for more UI components

**Instagram:** [@storymint.studio](https://instagram.com/storymint.studio)  
**GitHub:** [storymint-shivani](https://github.com/storymint-shivani)

-----

*Stop using spinners. Do this instead. 🔥*
