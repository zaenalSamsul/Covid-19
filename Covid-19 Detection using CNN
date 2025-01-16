# Latar Belakang

COVID-19 adalah penyakit yang disebabkan oleh virus SARS-CoV-2 yang menyebar dengan cepat ke seluruh dunia. Salah satu komplikasi paling serius dari COVID-19 adalah pneumonia, yang dapat menyebabkan gagal napas pada pasien kritis. Dengan tingginya jumlah kasus COVID-19, diperlukan sistem diagnosis berbasis teknologi yang dapat membantu tenaga kesehatan dalam mengidentifikasi penyakit secara cepat dan akurat melalui analisis citra radiologi, seperti X-ray dada.

Penggunaan teknologi kecerdasan buatan (AI), khususnya Convolutional Neural Network (CNN), telah menunjukkan potensi besar dalam menganalisis citra medis. CNN mampu mendeteksi pola-pola spesifik pada X-ray untuk membedakan antara pneumonia COVID-19 dan jenis pneumonia lainnya. Hal ini memungkinkan deteksi dini dan pengurangan beban kerja tenaga medis.

### Penelitian Terkait

1. **The diagnostic evaluation of Convolutional Neural Network (CNN) for the assessment of chest X-ray of patients infected with COVID-19**
   Studi oleh **Bukhari et al. (2020)** menggunakan model ResNet-50 dengan transfer learning untuk mengklasifikasikan X-ray dada menjadi tiga kategori: normal, pneumonia non-COVID-19, dan pneumonia COVID-19. Dataset terdiri dari 278 gambar, dan model mencapai akurasi 98,18% serta F1-score 98,19%. Penelitian ini menunjukkan bahwa CNN dapat secara efektif mengidentifikasi pola radiologis spesifik dari pneumonia COVID-19【12†source】.

2. **Chest X-ray image analysis and classification for COVID-19 pneumonia detection using Deep CNN**
   Studi oleh **Gao & Wang (2020)** mengembangkan sistem berbasis deep CNN untuk mendeteksi pneumonia COVID-19 dengan dataset berjumlah sekitar 1400 gambar. Sistem ini tidak hanya dapat membedakan pneumonia COVID-19 dari jenis pneumonia lainnya, tetapi juga dari X-ray dada normal. Dengan akurasi sekitar 90%, penelitian ini menekankan potensi AI dalam meningkatkan akurasi dan efisiensi diagnosis medis【13†source】.

### Gap Penelitian

Meskipun kedua jurnal menunjukkan hasil yang menjanjikan, terdapat beberapa kekurangan:
- **Ukuran Dataset:** Kedua penelitian menggunakan dataset yang relatif kecil, yang dapat memengaruhi kemampuan generalisasi model.
- **Evaluasi Klinis:** Tidak ada uji coba langsung di lingkungan klinis nyata untuk mengukur keefektifan sistem dalam praktik sehari-hari.
- **Komparasi Model:** Tidak ada perbandingan mendalam antara arsitektur CNN yang digunakan dengan model lainnya untuk menentukan performa terbaik.

### Perbandingan dengan Jurnal yang Akan Dibuat

Jurnal yang akan dibuat bertujuan untuk mengatasi kekurangan penelitian sebelumnya dengan pendekatan berikut:
1. **Dataset yang Lebih Besar:** Menggunakan dataset yang lebih komprehensif untuk meningkatkan kemampuan generalisasi model.
2. **Arsitektur Model yang Beragam:** Membandingkan beberapa arsitektur CNN seperti ResNet, VGG, dan EfficientNet untuk mengidentifikasi model terbaik.
3. **Validasi Klinis:** Melakukan evaluasi di lingkungan klinis untuk memverifikasi hasil penelitian.

Dengan pendekatan ini, penelitian diharapkan dapat menghasilkan sistem diagnosis pneumonia COVID-19 yang lebih akurat dan dapat diandalkan, memberikan kontribusi signifikan dalam mendukung tenaga kesehatan di tengah pandemi.

---

# Metode Penelitian

### Penggunaan Metode Convolutional Neural Network (CNN)

Metode penelitian menggunakan CNN dilakukan dengan tahapan sebagai berikut:

1. **Pengumpulan Dataset:**
   Dataset X-ray dada dikumpulkan dari sumber-sumber publik dan institusi medis yang terpercaya. Dataset ini mencakup kategori gambar normal, pneumonia non-COVID-19, dan pneumonia COVID-19. Data dilakukan preprocessing seperti resizing, normalisasi, dan augmentasi untuk meningkatkan variasi data.

2. **Arsitektur Model CNN:**
   Beberapa arsitektur CNN seperti ResNet, VGG, dan EfficientNet digunakan. CNN terdiri dari lapisan convolusi untuk ekstraksi fitur, pooling untuk mengurangi dimensionalitas, dan fully connected layers untuk klasifikasi akhir.

3. **Training dan Validasi Model:**
   Dataset dibagi menjadi data latih, validasi, dan uji. Model dilatih menggunakan optimasi seperti Adam atau SGD dan fungsi loss seperti categorical crossentropy. Teknik regularisasi seperti dropout diterapkan untuk menghindari overfitting.

4. **Evaluasi Model:**
   Model dievaluasi berdasarkan metrik seperti akurasi, precision, recall, dan F1-score. Selain itu, confusion matrix digunakan untuk menganalisis prediksi model.

5. **Visualisasi Hasil:**
   Heatmap seperti Grad-CAM digunakan untuk memahami area pada X-ray yang menjadi fokus model selama prediksi.

6. **Implementasi di Lingkungan Klinis:**
   Setelah model divalidasi, dilakukan pengujian langsung di lingkungan klinis untuk menilai performa dalam situasi nyata.

Pendekatan ini memastikan bahwa sistem diagnosis berbasis CNN tidak hanya akurat, tetapi juga dapat diimplementasikan secara efektif untuk mendukung tenaga kesehatan.

