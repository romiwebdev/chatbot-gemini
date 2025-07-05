# Proyek: Aplikasi Tanya Jawab AI

**Nama:** Muhromin

**Kelas:** SEC2025 Kelas 9

## Deskripsi Singkat

Proyek ini adalah implementasi chatbot AI sederhana menggunakan Gemini API. Program ini memungkinkan pengguna untuk mengajukan pertanyaan kepada AI, mencatat riwayat percakapan ke dalam sebuah file, dan menampilkan 3 percakapan terakhir saat chatbot dimulai.

## Fitur

* **Integrasi Gemini API:** Menggunakan model `gemini-1.5-flash` untuk menghasilkan jawaban yang relevan.
* **Penyimpanan Riwayat Chat:** Setiap pertanyaan dan jawaban disimpan dalam file `riwayat.txt`.
* **Menampilkan Riwayat Terakhir:** Saat memulai chatbot, 3 percakapan terakhir dari `riwayat.txt` akan ditampilkan.
* **Antarmuka Pengguna Sederhana:** Interaksi melalui konsol, mudah digunakan.

## Cara Menggunakan

### Prasyarat

* Python 3.x terinstal.
* Akses ke Google Gemini API dan memiliki API Key.

### Instalasi

1.  **Clone repositori ini:**
    ```bash
    git clone https://github.com/romiwebdev/chatbot-gemini
    cd chatbot-gemini
    ```

2.  **Instal pustaka yang diperlukan:**
    ```bash
    pip install google-generativeai
    ```

### Konfigurasi API Key

1.  Dapatkan API Key Anda dari Google AI Studio atau Google Cloud.
2.  Buka file `TanyaJawab_AI_Muhromin.ipynb` atau konversi menjadi file `.py`.
3.  Temukan baris berikut:
    ```python
    API_KEY = "API_KEY"
    ```
4.  Ganti `"API_KEY"` dengan API Key Anda yang sebenarnya:
    ```python
    API_KEY = "YOUR_YOUR_API_KEY_HERE"
    ```

### Menjalankan Chatbot

Jalankan skrip Python dari terminal Anda:

```bash
python TanyaJawab_AI_Muhromin.ipynb # Jika Anda menjalankannya sebagai notebook, Anda bisa membukanya di Colab atau Jupyter
````

Atau jika Anda mengkonversinya ke `.py` file, misalnya `chatbot.py`:

```bash
python chatbot.py
```

Setelah berjalan, Anda akan melihat pesan sambutan dan riwayat percakapan terakhir (jika ada). Anda bisa mulai mengetik pertanyaan Anda. Untuk keluar dari chatbot, ketik `keluar`.

## Struktur Proyek

  * `TanyaJawab_AI_Muhromin.ipynb`: File Jupyter Notebook utama yang berisi kode program.
  * `riwayat.txt`: File teks tempat riwayat percakapan disimpan.

## Refleksi Pribadi

Selama pengembangan proyek ini, tantangan utama yang saya hadapi adalah memahami struktur permintaan API dan pengaturan API Key. Saya belajar banyak tentang pentingnya membaca dokumentasi secara cermat. Saya bangga dapat membuat chatbot AI sederhana ini dengan fitur penyimpanan riwayat yang rapi.
