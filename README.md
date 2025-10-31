# Horizon Hub Website

Een moderne, responsive website gebouwd met HTML, CSS en JavaScript voor Horizon Hub.

## 📁 Project Structuur

```
horizonhub-website/
│
├── index.html              # Homepage
├── hoe-het-werkt.html     # Hoe het werkt pagina
├── over-ons.html          # Over ons pagina
├── partners.html          # Partners pagina
├── contact.html           # Contact pagina
│
├── css/
│   └── style.css          # Alle CSS styling
│
├── js/
│   └── main.js            # JavaScript functionaliteit
│
├── images/                # Afbeeldingen map (momenteel leeg)
│
└── README.md              # Dit bestand
```

## 🚀 Functies

### Design Kenmerken
- **Modern & Responsive**: Werkt perfect op desktop, tablet en mobiel
- **Gradient Kleuren**: Prachtige gradient achtergronden
- **Smooth Animaties**: Fade-in effecten en hover animaties
- **Glassmorphism**: Modern blur effect op navigation
- **Shadow Effects**: Professionele schaduwen voor depth

### Technische Features
- Fixed navigation met scroll effect
- Hamburger menu voor mobiele devices
- Smooth scroll voor anchor links
- Counter animaties voor statistieken
- Form validation op contact pagina
- Ripple effect op buttons
- Intersection Observer voor scroll animaties
- Parallax effect op hero sectie

### Pagina's

#### 1. **Home (index.html)**
- Hero sectie met call-to-action
- Missie sectie met features
- Statistieken sectie
- Proces preview
- CTA sectie

#### 2. **Hoe het werkt (hoe-het-werkt.html)**
- 3-fase proces uitleg
- AI en data-analyse mogelijkheden
- Voordelen sectie
- Gedetailleerde features

#### 3. **Over ons (over-ons.html)**
- Missie en visie
- Kernwaarden (6 items)
- Organisatie verhaal
- Toekomstvisie

#### 4. **Partners (partners.html)**
- Partnership types (6 categorieën)
- Voordelen van partnerschap
- Hoe partner worden proces
- CTA voor aanmelding

#### 5. **Contact (contact.html)**
- Contact formulier met validatie
- Contact informatie
- Kaart sectie
- FAQ sectie
- Social media links

## 🎨 Kleuren & Styling

### Primaire Kleuren
- Primary: `#6366f1` (Indigo)
- Secondary: `#8b5cf6` (Purple)
- Accent: `#ec4899` (Pink)

### Gradients
- Gradient 1: `#667eea → #764ba2`
- Gradient 2: `#f093fb → #f5576c`
- Gradient 3: `#4facfe → #00f2fe`

### Fonts
- Headers: **Poppins** (Google Fonts)
- Body: **Inter** (Google Fonts)

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Tablet: 481px - 768px
- Mobile: < 480px

## 🔧 Installatie & Gebruik

### Optie 1: Direct openen
1. Download en extract de ZIP file
2. Open `index.html` in uw browser
3. Klaar!

### Optie 2: Met Local Server (aanbevolen)
```bash
# Navigeer naar de project map
cd horizonhub-website

# Start een local server (Python)
python -m http.server 8000

# Of met PHP
php -S localhost:8000

# Of met Node.js (http-server)
npx http-server -p 8000
```

Open vervolgens `http://localhost:8000` in uw browser.

## 🖼️ Afbeeldingen Toevoegen

De `images/` map is momenteel leeg. U kunt eigen afbeeldingen toevoegen:

1. Plaats afbeeldingen in de `images/` map
2. Update de image URLs in de HTML bestanden
3. Aanbevolen formaten: JPG voor foto's, PNG voor illustraties, SVG voor logo's

### Aanbevolen Afbeeldingen
- Hero achtergrond (1920x1080px)
- Feature cards afbeeldingen (800x600px)
- Team foto's voor Over Ons (400x400px)
- Partner logo's (200x100px)

## 🔄 Aanpassen

### Kleuren Wijzigen
Open `css/style.css` en pas de CSS variabelen aan:
```css
:root {
    --primary-color: #jouw-kleur;
    --secondary-color: #jouw-kleur;
    /* etc. */
}
```

### Content Wijzigen
Pas de HTML bestanden direct aan. Alle content staat in platte HTML voor makkelijke bewerking.

### JavaScript Aanpassen
Pas `js/main.js` aan voor aangepaste functionaliteit.

## 📞 Contact Formulier

Het contact formulier is momenteel client-side. Voor daadwerkelijke verzending:

1. **PHP Backend**:
```php
<?php
// contact.php
if($_POST) {
    $name = $_POST['name'];
    $email = $_POST['email'];
    // Verwerk formulier...
}
?>
```

2. **JavaScript/Node.js**:
Gebruik services zoals:
- Formspree
- EmailJS
- SendGrid API
- Mailgun API

3. **Form Action**:
```html
<form action="uw-backend-url" method="POST">
```

## 🌐 Browser Support

- Chrome (laatste 2 versies)
- Firefox (laatste 2 versies)
- Safari (laatste 2 versies)
- Edge (laatste 2 versies)

## 📦 Dependencies

### External CDN's
- Font Awesome 6.4.0 (voor icons)
- Google Fonts (Inter & Poppins)

Deze worden automatisch geladen via CDN, geen installatie nodig.

## ⚡ Performance Tips

1. **Afbeeldingen optimaliseren**: Gebruik tools zoals TinyPNG
2. **CSS/JS minificeren**: Voor productie
3. **Lazy loading**: Voor afbeeldingen toevoegen
4. **Caching**: Server-side caching instellen

## 🔒 Beveiliging

Voor productie:
- Voeg HTTPS toe (SSL certificaat)
- Implementeer CSRF bescherming op formulieren
- Sanitize alle gebruikers input
- Voeg rate limiting toe op formulieren

## 📄 Licentie

© 2024 Horizon Hub. Alle rechten voorbehouden.

## 🤝 Credits

- Design & Development: Custom gemaakt voor Horizon Hub
- Icons: Font Awesome
- Fonts: Google Fonts
- Images: Placeholder images van Unsplash (vervang met eigen content)

## 📧 Support

Voor vragen of ondersteuning:
- Email: info@horizonhub.nl
- Tel: +31 (0)12 345 6789

---

**Veel succes met uw nieuwe website! 🚀**
