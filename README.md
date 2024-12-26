# streambuilder_mumtaz

Soal 12
- Pada langkah ke 3 terdapat sebuah class NumberStream dengan metode getNumbers, yang menghasilkan sebuah stream asinkron (Stream<int>). Metode ini menggunakan fungsi Stream.periodic untuk menghasilkan data secara berkala, yaitu setiap 1 detik (Duration(seconds: 1)). Pada setiap interval, sebuah angka acak antara 0 hingga 9 dibuat menggunakan kelas Random dan dikembalikan oleh stream. Operator yield* memastikan angka-angka tersebut diteruskan sebagai output dari stream, sehingga dapat didengarkan oleh pendengar (listener).
- Pada langkah ke 7 digunakan untuk membangun UI secara dinamis berdasarkan data dari sebuah stream (numberStream). StreamBuilder mendengarkan perubahan data pada stream, dengan nilai awal yang diatur melalui initialData: 0.
![alt text](images/soal12.gif)