# Zarzazorras - Art Collective Maqueta

This is a digital mockup created for **Zarzazorras**, an art collective focused on contemporary and experimental artistic practices. The collective aims to explore various artistic mediums and engage the community in creative expression.

The mockup utilizes the **Turn.js** library to simulate a flipbook experience, giving users a tactile, interactive way to engage with Zarzazorras' content. This project is designed to provide a visual and interactive preview of Zarzazorras' work, simulating the feeling of flipping through a physical book or magazine.

You can view the mockup at the following link:  

Zarzazorras Mockup
https://patriciodsgn.github.io/zarzazorras/


## Turn.js

Turn.js is a jQuery plugin that enhances web pages by creating a realistic page-flip transition, perfect for online publications, portfolios, or interactive catalogs. This project uses Turn.js to showcase the Zarzazorras artwork in a unique, book-like format.

### Usage

The flipbook for Zarzazorras is built using **HTML5** and **Turn.js**. Below are the key components used in this project:

### CSS Code:
```css
#magazine {
	width: 800px;
	height: 400px;
}
#magazine .turn-page {
	background-color: #ccc;
}
```

### HTML Code:
```html
<div id="magazine">
	<div><span class="text">Page 1 - Zarzazorras Introduction</span></div>
	<div><span class="text">Page 2 - Artworks Preview</span></div>
	<div><span class="text">Page 3 - Collective Vision</span></div>
</div>
```

### JavaScript Code:
```javascript
$('#magazine').turn({gradients: true, acceleration: true});
```

### Requirements

- jQuery 1.7 or later
- Turn.js plugin

### License

Turn.js is released under a non-commercial BSD license. For detailed usage and customization, refer to the full documentation [here](API-DOCUMENTATION.md).

---

This mockup serves as an experimental piece for Zarzazorras' ongoing projects, allowing the collective to present their artistic ideas in a dynamic digital format.