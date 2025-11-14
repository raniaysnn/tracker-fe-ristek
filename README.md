## Task Tracker FrontEnd
Di bagian frontend untuk aplikasi Task Tracker, yang dirancang untuk membantu mahasiswa untuk mengelola daftar matkul yang diambil, manajemen tugas, dan tracker tugas beserta deadline.
Opsional: Kalkulator nilai & bolos tracker. (Keseluruhan akan dibangun menggunakan framework React)
---
## Struktur Folder

### `src/` (Source)
Direktori utama yang berisi semua kode sumber aplikasi React.

| Direktori | Kegunaan |
| :--- | :--- |
| **`src/components/`** | Berisi komponen UI yang dapat digunakan kembali (*reusable components*) di berbagai halaman (misalnya, tombol, card tugas, form input, navigasi bar). |
| **`src/pages/`** | Berisi komponen utama yang merepresentasikan tampilan satu halaman penuh di aplikasi (misalnya, `Dashboard`, `CourseList`, `TaskDetail`). |
| **`src/api/`** | Tempat fungsi-fungsi untuk berinteraksi dengan **RESTful API Backend** (misalnya, fungsi untuk `GET /api/tasks` atau `POST /api/courses`). |
| **`src/utils/`** | Berisi fungsi-fungsi pembantu umum yang tidak terkait langsung dengan UI (misalnya, fungsi untuk memformat tanggal atau menghitung hari). |
| **`src/context/`** | (Untuk pemula, ini bisa diabaikan dulu, tetapi bagus jika ada) Tempat untuk meletakkan kode manajemen *state* global aplikasi. |
| **`src/assets/`** | Berisi *file* statis seperti gambar, ikon, atau *file* CSS. |

### File Utama

| File | Kegunaan |
| :--- | :--- |
| **`src/App.jsx`** | Komponen utama yang mengatur *routing* (perpindahan antar halaman) dan layout dasar aplikasi. |
| **`src/main.jsx`** | Titik masuk (*entry point*) aplikasi yang me-*render* komponen utama (`App.jsx`) ke dalam HTML. |
| **`package.json`** | Daftar semua pustaka (*library*) dan *framework* yang digunakan di proyek ini. |

---
