# Tugas Pratikum Pemrograman Web

# Langkah 1: Membuat File HTML Dasar

Buka aplikasi VS Code di laptop kamu.

Buat file baru dengan nama lab2_css_dasar.html.

Ketik struktur dasar HTML seperti berikut:
<img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/14600c06-8bda-4c0b-986a-c0d7e0172277" />

Simpan file tersebut.

Jalankan di browser untuk memastikan halaman HTML bisa tampil dengan judul CSS Dasar dan teks heading CSS Internal dan Inline CSS.

Selanjutnya buka pada brwoser untuk melihat hasilnya.

![WhatsApp Image 2025-09-29 at 20 14 15_41583519](https://github.com/user-attachments/assets/a284b4d9-88c7-4201-94cc-373da8c7c64a)

# Langkah 2: Menambahkan CSS Internal

Masih di file lab2_css_dasar.html, tambahkan tag <style> di dalam bagian <head>. Tag ini dipakai buat nulis CSS Internal, yaitu CSS langsung di dalam file HTML.

Ketik kode CSS berikut:

<img width="842" height="535" alt="Screenshot 2025-09-29 121006" src="https://github.com/user-attachments/assets/083bfc3b-b173-4b89-8d72-87b99522a42f" />

Simpan file.

Coba jalankan di browser, kita melihat beberapa perubahan:

Font teks berubah jadi Open Sans.

Bagian header punya garis bawah warna biru.

Judul < h1 > berwarna biru tua, posisinya tengah, dan ada jarak.

Teks miring < i > di dalam < h1 > berubah warna abu-abu 


lakukan refresh pada browser untuk melihat hasilnya.
<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/b906f18b-42c3-49ab-8eea-ef4e7300e792" />

# Langkah 3: Menyisipkan CSS Eksternal

Untuk menggunakan CSS eksternal, kita perlu membuat sebuah file CSS terpisah (misalnya style_eksternal.css) lalu menghubungkannya ke dalam file HTML. Cara menghubungkannya adalah dengan menggunakan tag <link> di dalam bagian <head> pada HTML.

Kode yang digunakan:

<img width="781" height="74" alt="Screenshot 2025-09-29 124417" src="https://github.com/user-attachments/assets/7b7ff8aa-056b-4e03-825a-eec5066280d2" />

Setelah kode < link > ditambahkan di dalam < head >, maka tampilan halaman HTML akan mengikuti aturan gaya (style) yang sudah ditulis di dalam file style_eksternal.css.
refresh kembali browser untuk melihat perubahannya.

<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/0b43f8ab-b2bc-4e35-b40d-1e039e07ba10" />

# Langkah 4: Membuat CSS eksternal 

Buat sebuah file baru dengan nama style_eksternal.css, lalu isikan kode CSS berikut untuk mengatur tampilan navigasi:

<img width="436" height="398" alt="Screenshot 2025-09-29 204749" src="https://github.com/user-attachments/assets/549d7dd5-068c-451e-8d44-828824a99467" />


Setelah itu, hubungkan file CSS tersebut ke dalam dokumen HTML dengan menambahkan kode berikut pada bagian < head >:

<img width="781" height="74" alt="Screenshot 2025-09-29 124417" src="https://github.com/user-attachments/assets/93379d3f-2105-4e8e-9b97-1fa19e4a0479" />

Selanjutnya refresh kembali browser untuk melihat perubahannya.
<img width="1920" height="1080" alt="Screenshot (79)" src="https://github.com/user-attachments/assets/eb32bd28-f26f-432a-8007-4f4350720cf0" />

# Langkah 5: Menambahkan CSS Selector

Berikutnya kita dapat menambahkan aturan CSS dengan memanfaatkan ID Selector dan Class Selector. Masukkan kode berikut ke dalam file style_eksternal.css:

<img width="334" height="495" alt="Screenshot 2025-09-29 124615" src="https://github.com/user-attachments/assets/e9baf999-de5b-40fb-87dd-3e34256b5ea6" />

Setelah menambahkan kode ini, simpan file CSS lalu perbarui halaman di browser untuk melihat hasil perubahannya.

<img width="1920" height="1080" alt="Screenshot (80)" src="https://github.com/user-attachments/assets/e7164b3a-196b-4cac-a30f-19cf77715c7c" />

# Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

# JAWABAN 

1. Pada versi sebelumnya, tampilan web masih menggunakan warna background standar, ukuran font kecil, serta padding dan margin yang sempit.

Kode yang digunakan:

<img width="1920" height="1080" alt="Screenshot (82)" src="https://github.com/user-attachments/assets/54dbb8aa-b2f0-4439-98a5-104e5a2107a7" />
<img width="1920" height="1080" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/fde5fbf1-0d69-488f-b990-2a74c8fab775" />

dan hasil dari kode tersebut


<img width="1920" height="1080" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/451c9051-bf8a-4319-9529-9d5f0208285f" />

2. h1 { ... }

Disebut selektor elemen.

Digunakan untuk memberikan gaya ke semua tag < h1 > di halaman web.

Contoh: kalau kita tulis h1 {color: green;}, maka semua teks < h1 > akan jadi hijau, baik itu di header, di intro, atau di bagian lain.

#intro h1 { ... }

Disebut selektor spesifik (ID + elemen).

Hanya berlaku untuk tag < h1 > yang ada di dalam elemen dengan id “intro”.

Jadi misalnya ada < div id="intro" >< h1 > Judul < /h1 > < /div  >, maka hanya judul itu saja yang kena aturan.

3. Apabila ada deklarasi CSS secara internal, eksternal, dan inline pada elemen yang sama, maka yang ditampilkan browser adalah deklarasi inline CSS. Hal ini karena inline CSS memiliki tingkat prioritas (specificity) paling tinggi dibandingkan internal maupun eksternal CSS.

Urutan prioritas CSS adalah:

Eksternal CSS → paling lemah.

Internal CSS → lebih kuat dari eksternal.

Inline CSS → paling kuat.

!important → akan mengalahkan semuanya.

Contohnya


<img width="906" height="421" alt="Screenshot 2025-09-29 213627" src="https://github.com/user-attachments/assets/ccf97742-ba4e-4c65-b87f-96a669143a4a" />

4. Apabila sebuah elemen HTML memiliki ID dan Class sekaligus, lalu keduanya memiliki deklarasi CSS, maka yang ditampilkan pada browser adalah deklarasi CSS dari ID. Hal ini karena selector ID memiliki tingkat prioritas lebih tinggi dibanding selector Class.

Contohnya

<img width="885" height="513" alt="Screenshot 2025-09-29 213913" src="https://github.com/user-attachments/assets/2eb7e351-fe3b-4cc5-b455-96c5922ed71f" />

Hasil di browser:
Teks “Ini contoh paragraf” akan berwarna merah, karena deklarasi dengan ID lebih spesifik dan lebih tinggi prioritasnya daripada Class.













