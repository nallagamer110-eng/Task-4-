# Image Display Page

A simple HTML and CSS project demonstrating viewport units, proper spacing, and custom button styling without using Flex, overflow:hidden, or position relative/absolute.

## Files Included

- `index.html` - The main HTML file with image display div and button
- `style.css` - The CSS file containing all styling rules
- `README.md` - This documentation file
- `image.jpg` - Replace with your actual image file

## Project Steps Overview

### 1. HTML Setup ✅
- Defined document structure with necessary HTML tags (`<!DOCTYPE>`, `<html>`, `<head>`, `<body>`)
- Set document title: "Image Display Page"
- Linked external stylesheet (`style.css`) using `<link>` tag

### 2. Body Content ✅
- Created a `<div>` with class `"image-section"` for image display
- Inserted an `<img>` tag within the div
- Added a `<button>` with class `"custom-button"` for user interaction

### 3. CSS Styling ✅
- **Equal spacing**: 25% from left and right (50vw width with auto margin)
- **Top/bottom spacing**: 10% from top and bottom (10vh margin)
- **Button customization**: Gradient background (`linear-gradient(135deg, #667eea 0%, #764ba2 100%)`), custom font settings
- **Box Sizing**: `box-sizing: border-box` applied globally and on elements
- **No scroll**: Page layout designed to fit viewport without scrolling
- **Viewport units**: Used `vw` (viewport width) and `vh` (viewport height) throughout

### 4. Final Steps ✅
- All HTML tags properly closed
- ❌ No Flex used
- ❌ No `overflow: hidden` used
- ❌ No `position: relative` or `position: absolute` used

## CSS Techniques Used

| Technique | Implementation | Purpose |
|-----------|---------------|---------|
| Viewport Units | `50vw`, `10vh`, `18px` | Responsive sizing based on screen |
| Box Sizing | `box-sizing: border-box` | Consistent padding/border calculation |
| Gradient Background | `linear-gradient(135deg, #667eea, #764ba2)` | Modern button appearance |
| Text Alignment | `text-align: center` | Center content without Flex |
| Transitions | `transition: transform 0.2s` | Smooth hover effects |

## How to Run

1. Save all files in the same folder: