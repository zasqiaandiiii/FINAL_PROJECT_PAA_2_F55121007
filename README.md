# FINAL_PROJECT_PAA_2_F55121007
# ANALISIS ALGORITMA 
# Bubble Sort dan Insertion Sort Analisis Algoritma
# **(Worst Case):**
Kasus terburuk terjadi ketika data yang akan diurutkan sudah dalam keadaan terbalik atau hampir terbalik. Misalnya, jika kita memiliki array angka yang terurut secara menaik dan kita ingin mengurutkannya secara menurun. Dalam kasus ini, baik Bubble Sort maupun Insertion Sort akan mengalami kinerja terburuk.

1. Bubble Sort pada kasus terburuk memiliki kompleksitas waktu O(n^2), dimana n adalah jumlah elemen dalam array. Hal ini disebabkan karena pada setiap iterasi, algoritma harus membandingkan dan menukar elemen secara berulang-ulang untuk memindahkan elemen-elemen terbesar ke bagian akhir array.

2. Insertion Sort pada kasus terburuk juga memiliki kompleksitas waktu O(n^2). Pada setiap iterasi, algoritma harus membandingkan elemen yang akan diinsert dengan setiap elemen sebelumnya dalam array, dan jika ditemukan elemen yang lebih besar, elemen tersebut harus digeser ke kanan.

## **(Best Case):**
Kasus terbaik terjadi ketika data yang akan diurutkan sudah dalam keadaan terurut atau hampir terurut. Misalnya, jika kita memiliki array angka yang sudah terurut secara menaik dan kita ingin mengurutkannya secara menaik lagi. Dalam kasus ini, baik Bubble Sort maupun Insertion Sort akan memiliki kinerja terbaik.

1. Bubble Sort pada kasus terbaik memiliki kompleksitas waktu O(n), karena algoritma akan langsung berhenti setelah satu iterasi penuh tanpa ada pertukaran elemen yang dilakukan. Ini karena tidak ada perubahan yang terjadi saat membandingkan elemen yang sudah terurut dengan elemen lainnya.

2. Insertion Sort pada kasus terbaik juga memiliki kompleksitas waktu O(n), karena algoritma hanya perlu membandingkan elemen yang akan diinsert dengan elemen sebelumnya dalam array yang sudah terurut. Karena elemen-elemen sebelumnya sudah terurut, hanya satu perbandingan yang perlu dilakukan pada setiap iterasi.

## **(Average Case):**
Kasus rata-rata adalah situasi yang umum terjadi ketika data yang akan diurutkan tidak dalam keadaan terurut, tetapi juga tidak dalam keadaan terbalik. Dalam kasus ini, baik Bubble Sort maupun Insertion Sort akan memiliki kinerja yang sama-sama buruk.
1. Bubble Sort pada kasus rata-rata memiliki kompleksitas waktu O(n^2), karena algoritma akan melakukan pertukaran elemen dalam setiap iterasi sampai array benar-benar terurut. Jumlah perbandingan dan pertukaran yang dilakukan adalah tinggi dalam kasus rata-rata.

2. Insertion Sort pada kasus rata-rata juga memiliki kompleksitas waktu O(n^2). Algoritma akan melakukan perbandingan dan pergeseran elemen-elemen dalam setiap iterasi sampai array benar-benar terurut. Meskipun Insertion Sort memiliki kinerja yang lebih baik daripada Bubble Sort dalam beberapa kasus, kompleksitas waktu kasus rata-rata keduanya tetap sama.

Dalam kesimpulan, Bubble Sort dan Insertion Sort memiliki kinerja yang serupa dalam kasus terburuk dan kasus rata-rata, yaitu O(n^2). Namun, dalam kasus terbaik, keduanya memiliki perbedaan signifikan, di mana Bubble Sort memiliki kompleksitas waktu O(n), sedangkan Insertion Sort tetap O(n^2). Oleh karena itu, dalam situasi di mana data sudah hampir terurut, Insertion Sort cenderung menjadi pilihan yang lebih baik daripada Bubble Sort.

# ANALISIS ALGORITMA
# TSP dan Dijkstra 

# **Worst case:**

* Algoritma TSP memiliki kompleksitas waktu yang sangat tinggi dengan faktorial O(n!), di mana n adalah jumlah vertex. Dalam kasus terburuk, ketika jumlah vertex besar, algoritma ini membutuhkan waktu yang sangat lama dan tidak efisien karena harus mengeksplorasi semua kemungkinan permutasi.

* Algoritma Dijkstra memiliki kompleksitas waktu O(|V|^2), di mana |V| adalah jumlah vertex. Dalam kasus terburuk, jika terdapat banyak vertex, algoritma ini akan membutuhkan waktu yang cukup lama karena perlu menghitung jarak terpendek dari setiap vertex ke semua vertex lainnya.

# **Best case:**

* Algoritma TSP memiliki kinerja terbaik saat hanya terdapat sedikit vertex yang saling terhubung, sehingga jumlah permutasi yang dihasilkan sedikit. Dalam kasus ini, algoritma dapat menemukan jalur terpendek dengan cepat.

* Algoritma Dijkstra akan memiliki kinerja terbaik jika hanya terdapat sedikit vertex yang saling terhubung atau jika titik awal dan akhir langsung terhubung. Dalam kasus ini, algoritma dapat menemukan jalur terpendek dengan cepat tanpa harus mengunjungi banyak vertex.

#**Average case:**

* Algoritma TSP memiliki kompleksitas waktu faktorial O(n!). Kinerja algoritma ini sangat dipengaruhi oleh jumlah vertex yang ada. Semakin banyak vertex, semakin lama waktu yang dibutuhkan untuk menghitung jalur terpendek secara keseluruhan.

* Algoritma Dijkstra memiliki kompleksitas waktu O(|V|^2), di mana |V| adalah jumlah vertex. Pada kasus rata-rata, kinerja algoritma ini tergantung pada jumlah vertex dan banyaknya edge yang terhubung. Semakin banyak vertex dan edge yang ada, semakin lama waktu yang diperlukan untuk mencari jalur terpendek.

*Perlu diingat bahwa analisis kompleksitas di atas mengasumsikan bahwa grafik tidak memiliki struktur khusus yang dapat mempengaruhi kinerja algoritma. Terdapat juga teknik dan optimasi lain yang dapat digunakan untuk meningkatkan efisiensi algoritma TSP dan Dijkstra dalam kasus-kasus tertentu.*


