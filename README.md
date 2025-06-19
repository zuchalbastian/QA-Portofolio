
# 🧪 QA-Portofolio by Zuchal Bastian

Selamat datang di portofolio QA saya!  
Repository ini berisi kumpulan dokumentasi pengujian manual yang saya susun berdasarkan pengalaman sebagai **Software Quality Assurance**.

Tujuan dari repo ini adalah untuk menunjukkan **kemampuan QA end-to-end**, termasuk penulisan test case, pelaporan bug, dan penerapan Behavior Driven Development (BDD) menggunakan Gherkin.

---

## 📁 Struktur Repository

```
QA-Portofolio/
├── Test_Cases/             # Test case manual (login, checkout, dll)
├── Bug_Reports/            # Laporan bug (dengan langkah & bukti)
├── Gherkin_Scenarios/      # Test case dalam format Gherkin
├── Docs/                   # Test Plan, Checklist, dan dokumen pendukung
├── Screenshots/            # Bukti visual dari bug atau hasil pengujian
└── README.md               # Dokumentasi proyek (file ini)
```

---

## 🧰 Apa yang Ada di Dalamnya?

### ✅ Test Case Manual
Dokumen Excel/Sheet berisi skenario pengujian aplikasi:
- Login dengan kredensial valid/tidak valid
- Add to Cart & Checkout
- Validasi UI dan error message

### 🐞 Bug Report
Dokumen bug report dengan format profesional:
- Bug ID, Severity, Prioritas
- Langkah reproduksi
- Expected vs Actual Result
- Screenshot pendukung

### 🧠 Test Case Gherkin (BDD)
Contoh penulisan test case menggunakan format **Given-When-Then** (Cucumber):
```gherkin
Scenario: Login berhasil
  Given pengguna di halaman login
  When memasukkan username dan password yang valid
  Then pengguna diarahkan ke halaman dashboard
```

### 🔁 Scenario Outline
Menguji banyak input berbeda dalam satu skenario:
```gherkin
Scenario Outline: Cari produk
  When user mencari "<keyword>"
  Then hasil menampilkan produk terkait

Examples:
  | keyword     |
  | Laptop      |
  | Smartphone  |
```

---

## 🎯 Tujuan Proyek

- Menunjukkan kemampuan QA dalam menyusun dokumentasi yang sistematis
- Mendemonstrasikan praktik QA profesional sesuai standar industri
- Menjadi referensi atau bukti portofolio saat melamar pekerjaan sebagai QA

---

## 🚀 Teknologi & Tools

| Area              | Tools Digunakan            |
|-------------------|----------------------------|
| Dokumentasi       | Excel, Google Sheets, Docs |
| Bug Tracking      | Manual (Word), Trello       |
| BDD               | Gherkin, Cucumber Syntax    |
| Screenshot        | Lightshot, Snipping Tool    |

---

## 🔗 Live Link
GitHub: [https://github.com/zuchalbastian/QA-Portofolio](https://github.com/zuchalbastian/QA-Portofolio)

---

## 🙌 Kontribusi

Proyek ini bersifat open-source dan bisa digunakan sebagai referensi oleh siapa pun yang ingin membangun portofolio QA.  
Silakan **fork**, gunakan, atau beri ⭐️ jika bermanfaat!

---

## 📄 Lisensi

MIT License – silakan gunakan, modifikasi, dan sebarkan dengan bebas selama mencantumkan kredit.

---

Terima kasih sudah mampir!  
Untuk pertanyaan atau kolaborasi, hubungi saya di LinkedIn: [linkedin.com/in/zuchalbastian]([https://www.linkedin.com/in/zuchalbastian](https://www.linkedin.com/in/zuchal-ari-bastian-a88469195/))
