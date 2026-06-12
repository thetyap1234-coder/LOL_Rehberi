# 🌟 League of Legends - Dinamik Şampiyon Rehberi & Galerisi

Riot Games'in resmi **Data Dragon API** altyapısını kullanarak oyundaki tüm şampiyonları anlık olarak çeken, modern arayüzlü ve dinamik filtreleme özelliklerine sahip bir web uygulaması. Proje, League of Legends evreninin o ikonik atmosferini web ortamına taşımak amacıyla **Hextech Altını** ve **Koyu Mod** teması baz alınarak tasarlanmıştır.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Riot Games](https://img.shields.io/badge/Riot_Games-EB0029?style=for-the-badge&logo=riotgames&logoColor=white)

---

## 🚀 Özellikler

* **Canlı Veri Entegrasyonu (Riot API):** Şampiyon bilgileri, görselleri ve yetenek ikonları doğrudan Riot Games Data Dragon sunucularından asenkron (`fetch`) olarak çekilir. Oyun güncellendikçe site otomatik olarak güncellenir.
* **Gelişmiş Arama & Kombin Filtreleme:** Kullanıcılar şampiyon isimlerine göre arama yapabilir ve aynı anda rollerine (Suikastçı, Büyücü, Tank, vb.) göre anlık filtreleme uygulayabilir.
* **Hextech UI/UX Tasarımı:** LoL evrenine sadık kalınarak hazırlanan Gece Mavisi, Koyu Gri ve Hextech Altını (`#c8aa6e`) renk paleti, özel tarayıcı kaydırma çubuğu (scrollbar) ve akıcı kart animasyonları.
* **Dinamik Detay Modalı (Açılır Pencere):** Herhangi bir şampiyona tıklandığında açılan, şampiyonun geniş hikayesini (Lore) ve API'den gelen resmi yetenek ikonlarını dinamik olarak yükleyen gelişmiş detay ekranı.
* **3 Sütunlu Profesyonel Footer:** Ekran boyutuna göre şekil alan, Bootstrap `col-md-4` mantığıyla inşa edilmiş; Hakkında, Hızlı Linkler ve İletişim bilgilerini barındıran responsive alt bilgi alanı.
* **Tamamen Mobil Uyumlu (Responsive):** CSS Grid ve Flexbox altyapısı sayesinde mobil, tablet ve masaüstü cihazlarda kusursuz görüntüleme.

---

## 🛠️ Kullanılan Teknolojiler

* **Semantic HTML5:** Erişilebilir ve SEO dostu sayfa yapısı.
* **CSS3 (Grid & Flexbox):** Responsive düzen tasarımı, özel animasyonlar ve neon ışıma efektleri.
* **Vanilla JavaScript (ES6+):** Harici hiçbir kütüphane (JQuery vb.) kullanılmadan, asenkron `Fetch API` ve dinamik DOM yönetimi ile geliştirilmiş filtreleme motoru.
* **Riot Data Dragon API:** Güncel oyun verilerinin çekildiği resmi kaynak.

---

## 💻 Kurulum ve Çalıştırma

Proje tamamen bağımsız (Vanilla JS) olarak geliştirildiği için herhangi bir derleyiciye veya paket yöneticisine (NPM, Webpack vb.) ihtiyaç duymaz.

1.  Projeyi bilgisayarınıza klonlayın:
    ```bash
    git clone [https://github.com/kullanici-adiniz/lol-champion-gallery.git](https://github.com/kullanici-adiniz/lol-champion-gallery.git)
    ```
2.  Proje klasörüne gidin:
    ```bash
    cd lol-champion-gallery
    ```
3.  `index.html` dosyasını herhangi bir tarayıcıda çift tıklayarak açın veya bir kod editörü (VS Code gibi) üzerinden **Live Server** ile çalıştırın.

---

## 📂 Proje Yapısı

```text
lol-champion-gallery/
resim dosyaları , css ve js dosyaları ihtiyaç duyulmadığı için sonradan kaldırılmıştır !!!
├── index.html          # Ana HTML iskeleti, CSS stilleri ve JS motoru (Tek sayfa mimarisi)
└── README.md           # Proje hakkında bilgilendirme dosyası

URL:
https://cozy-dragon-0a81c5.netlify.app/
resim dosyalrı , css ve js dosyalarına ihtiyaç duyulmadığı için sonradan kaldırılmıştır
