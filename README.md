# Gadoeh Rasa - Landing Page Template

Template landing page modern untuk brand Gadoeh Rasa dengan animasi yang menarik dan user experience yang optimal.

## 🚀 Fitur Utama

### Design & UI/UX
- ✨ Design modern dan eye-catching dengan skema warna kuning krem
- 📱 Fully responsive untuk semua device (mobile, tablet, desktop)
- 🎨 Smooth animations menggunakan AOS (Animate On Scroll)
- 🖼️ Image gallery dengan Swiper slider
- 🎭 Interactive hover effects
- 💫 Floating dan bouncing animations untuk mascot

### Teknologi yang Digunakan
- **HTML5** - Struktur semantic dan modern
- **CSS3** - Styling dengan custom properties dan animations
- **JavaScript (ES6+)** - Interactive features
- **Bootstrap 5.3** - Responsive framework
- **AOS (Animate On Scroll)** - Scroll animations
- **Swiper.js** - Touch slider untuk gallery
- **Font Awesome 6** - Icons
- **Google Fonts (Poppins)** - Typography

### Sections
1. **Navigation Bar** - Sticky navbar dengan smooth scroll
2. **Hero Section** - Headline besar dengan product showcase
3. **About Section** - Deskripsi brand dengan 3 feature highlights
4. **Video Section** - Video player dengan mascot animation
5. **Product Gallery** - Swiper slider untuk product images
6. **Why Choose Us** - Keunggulan produk dengan cards
7. **Best Seller** - Highlight produk unggulan
8. **Footer** - Contact info dan social media links

## 📦 Struktur File

```
gadoeh-rasa/
│
├── index.html          # File HTML utama
├── style.css           # Custom CSS styles
├── script.js           # JavaScript functionality
└── README.md          # Dokumentasi (file ini)
```

## 🎨 Customization Guide

### Mengubah Warna
Edit CSS variables di file `style.css`:

```css
:root {
    --primary-color: #F4D03F;      /* Kuning cerah */
    --secondary-color: #F39C12;    /* Orange */
    --text-dark: #2C3E50;          /* Teks gelap */
    --text-light: #7F8C8D;         /* Teks abu-abu */
}
```

### Mengganti Logo
1. Buat image logo Anda
2. Ganti div `.logo-circle` di navbar dengan:
```html
<img src="path/to/your/logo.png" alt="Logo" class="logo-img">
```

### Mengganti Gambar Produk
1. Siapkan gambar produk Anda (format: JPG, PNG, WebP)
2. Ganti URL gambar di `index.html`:
```html
<img src="path/to/your/image.jpg" alt="Product">
```

### Menambah/Mengurangi Menu
Edit bagian navbar di `index.html`:
```html
<li class="nav-item">
    <a class="nav-link" href="#section-id">MENU NAME</a>
</li>
```

## 🎬 Animation Features

### 1. AOS (Animate On Scroll)
Animasi yang muncul saat scroll:
- `fade-up` - Muncul dari bawah
- `fade-down` - Muncul dari atas
- `fade-right` - Muncul dari kanan
- `fade-left` - Muncul dari kiri
- `zoom-in` - Zoom in effect

Contoh penggunaan:
```html
<div data-aos="fade-up" data-aos-duration="1000">
    Content here
</div>
```

### 2. CSS Animations
- `floating` - Efek melayang untuk produk
- `bounce` - Efek bouncing untuk mascot
- `pulse` - Efek pulse/berkedip

### 3. Hover Effects
- Cards yang terangkat saat hover
- Icons yang berputar
- Buttons dengan shadow effect

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 991px
- **Desktop**: 992px - 1199px
- **Large Desktop**: ≥ 1200px

## 🔧 Instalasi & Setup

### 1. Download Files
Download semua file (index.html, style.css, script.js)

### 2. Struktur Folder
Buat folder project dan masukkan semua file

### 3. Buka di Browser
Double-click file `index.html` atau buka dengan Live Server

### 4. (Optional) Setup Local Server
```bash
# Menggunakan Python
python -m http.server 8000

# Menggunakan Node.js
npx http-server

# Menggunakan PHP
php -S localhost:8000
```

## 🎯 Best Practices

### Performance Optimization
1. **Compress Images**: Gunakan TinyPNG atau ImageOptim
2. **Lazy Loading**: Tambahkan `loading="lazy"` pada images
3. **Minify CSS/JS**: Untuk production, minify file CSS dan JS
4. **CDN**: Libraries sudah menggunakan CDN untuk load time yang lebih cepat

### SEO Optimization
1. Tambahkan meta tags di `<head>`:
```html
<meta name="description" content="Deskripsi website">
<meta name="keywords" content="keyword1, keyword2">
<meta property="og:title" content="Gadoeh Rasa">
<meta property="og:image" content="image-url.jpg">
```

2. Gunakan semantic HTML tags
3. Optimize alt text untuk images
4. Add schema markup untuk better search results

## 🛠️ Customization Examples

### Menambah Section Baru
```html
<section id="new-section" class="py-5">
    <div class="container">
        <h2 data-aos="fade-up">Section Title</h2>
        <div class="row">
            <!-- Content here -->
        </div>
    </div>
</section>
```

### Menambah Product Card
```html
<div class="col-md-4" data-aos="zoom-in">
    <div class="product-card">
        <img src="product.jpg" alt="Product">
        <h4>Product Name</h4>
        <p>Product Description</p>
        <button class="btn btn-primary">Order Now</button>
    </div>
</div>
```

### Menambah Testimonial
```html
<div class="testimonial-card">
    <p class="testimonial-text">"Customer review here..."</p>
    <div class="testimonial-author">
        <img src="avatar.jpg" alt="Customer">
        <div>
            <h5>Customer Name</h5>
            <span>⭐⭐⭐⭐⭐</span>
        </div>
    </div>
</div>
```

## 🔗 Social Media Integration

Ganti link social media di footer dan navbar:
```html
<a href="https://facebook.com/yourpage"><i class="fab fa-facebook-f"></i></a>
<a href="https://instagram.com/yourprofile"><i class="fab fa-instagram"></i></a>
<a href="https://pinterest.com/yourprofile"><i class="fab fa-pinterest"></i></a>
```

## 📧 Contact Form (Optional)

Tambahkan contact form di section baru:
```html
<form id="contactForm">
    <input type="text" placeholder="Nama" required>
    <input type="email" placeholder="Email" required>
    <textarea placeholder="Pesan" required></textarea>
    <button type="submit">Kirim</button>
</form>
```

## 🎨 Color Schemes Alternatives

### Scheme 1: Blue Theme
```css
--primary-color: #3498db;
--secondary-color: #2980b9;
```

### Scheme 2: Green Theme
```css
--primary-color: #2ecc71;
--secondary-color: #27ae60;
```

### Scheme 3: Purple Theme
```css
--primary-color: #9b59b6;
--secondary-color: #8e44ad;
```

## 🐛 Troubleshooting

### Animasi Tidak Jalan
- Pastikan AOS library sudah loaded
- Check console untuk errors
- Verify AOS.init() sudah dipanggil

### Swiper Tidak Muncul
- Check apakah Swiper CSS dan JS sudah loaded
- Verify class names sudah benar
- Check console untuk errors

### Layout Rusak di Mobile
- Test dengan Chrome DevTools
- Check media queries
- Verify Bootstrap classes

## 📚 Resources & Documentation

- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [AOS Animation Library](https://michalsnik.github.io/aos/)
- [Swiper Documentation](https://swiperjs.com/)
- [Font Awesome Icons](https://fontawesome.com/icons)

## 💡 Tips & Tricks

1. **Fast Development**: Gunakan Bootstrap classes untuk spacing (mt-3, mb-5, py-4, etc)
2. **Consistent Spacing**: Gunakan 8px grid system (8, 16, 24, 32, 40, etc)
3. **Readable Code**: Comment your code untuk maintenance yang lebih mudah
4. **Version Control**: Gunakan Git untuk track changes
5. **Testing**: Test di berbagai browser dan devices

## 🎓 Learning Resources

- HTML/CSS: [MDN Web Docs](https://developer.mozilla.org/)
- JavaScript: [JavaScript.info](https://javascript.info/)
- Bootstrap: [Bootstrap Official](https://getbootstrap.com/)
- Web Animation: [Web Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API)

## 📝 License

Template ini free untuk digunakan untuk personal maupun commercial projects.

## 🤝 Support

Jika ada pertanyaan atau butuh bantuan customization, silahkan hubungi:
- Email: support@gadoehrasa.com
- Instagram: @gadoehrasa
- Website: www.gadoehrasa.com

## 🎉 Credits

Design inspired by: Gadoeh Rasa Brand
Developed with: Love and Coffee ☕

---

**Happy Coding! 🚀**

Made with ❤️ for Gadoeh Rasa
