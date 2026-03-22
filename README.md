
## 📚 Öğrendiklerim

### Core JavaScript
`let` / `const` &nbsp;·&nbsp; Arrow functions &nbsp;·&nbsp; `if/else`, ternary &nbsp;·&nbsp; `for...of` döngüsü &nbsp;·&nbsp; Array metotları (`map`, `filter`, `find`, `push`) &nbsp;·&nbsp; Template literals &nbsp;·&nbsp; `Number()` dönüşümü

### DOM & Events
`getElementById` / `querySelector` &nbsp;·&nbsp; `createElement` / `appendChild` &nbsp;·&nbsp; `innerHTML` / `textContent` / `classList` &nbsp;·&nbsp; `onclick` / `addEventListener` &nbsp;·&nbsp; `keypress` / `keydown`

### Veri Yönetimi
LocalStorage (CRUD) &nbsp;·&nbsp; `JSON.stringify` / `JSON.parse` &nbsp;·&nbsp; State yönetimi &nbsp;·&nbsp; Form validasyonu

### API & Async
`fetch` / `async` / `await` &nbsp;·&nbsp; `try/catch` hata yönetimi &nbsp;·&nbsp; Gerçek API entegrasyonu

---

## 🛠️ Projeler

| # | Proje | Öne Çıkan Özellikler |
|---|-------|----------------------|
| 1 | 🧾 **TODO App** | CRUD, filtreleme, sayaç, LocalStorage, Enter kısayolu |
| 2 | 🔐 **Login Sistemi** | Form validasyonu, state switching, puan sistemi, LocalStorage |
| 3 | 🛒 **Ürün Sepeti** | Dinamik ürün ekleme, adet & fiyat hesaplama, silme, LocalStorage |
| 4 | 🌤️ **Hava Durumu** | wttr.in API, async/await, JSON parsing, son arama hafızası |
| 5 | 🛍️ **Alışveriş Sepeti** | Ürün listeleme, sepete ekleme, toplam hesaplama, LocalStorage |

---

## 💻 Kod Örnekleri
```js
// Filtreleme
const tamamlananlar = tasks.filter(task => task.tamam);

// LocalStorage'a kaydetme
localStorage.setItem("tasks", JSON.stringify(tasks));

// API çekme
async function havaGetir(sehir) {
  const res = await fetch(`https://wttr.in/${sehir}?format=j1`);
  return await res.json();
}

// DOM'a eleman ekleme
const kart = document.createElement("div");
liste.appendChild(kart);
` ` `

---

## 📈 İlerleme

` ` `
Core JS      ████████████████████  %100
DOM & Events ████████████████████  %100
Veri Yönt.   ████████████████████  %100
API & Async  ████████████████████  %100
Projeler     ████████████████████  5/5
` ` `

---

*Öğrenmeye devam ediyorum. *
```

