# Analisis Sentimen dengan Naive Bayes

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap data teks menggunakan algoritma **Naive Bayes**, yang merupakan salah satu metode supervised learning yang populer untuk klasifikasi teks.

## Deskripsi Proyek

Notebook ini berisi proses lengkap analisis sentimen, dimulai dari:

1. **Import Library**  
   Menggunakan pustaka populer seperti `pandas`, `sklearn`, dan `nltk`.

2. **Load Data**  
   Dataset dimuat dari file CSV dan diproses ke dalam format dataframe.

3. **Preprocessing**  
   Tahapan pembersihan data termasuk:
   - Case folding
   - Menghapus tanda baca dan angka
   - Tokenisasi
   - Stopword removal
   - Stemming

4. **Ekstraksi Fitur**  
   Menggunakan **TF-IDF Vectorizer** untuk mengubah teks menjadi representasi numerik.

5. **Modeling**  
   Membangun model klasifikasi menggunakan algoritma **Multinomial Naive Bayes** dari `sklearn`.

6. **Evaluasi**  
   Mengukur akurasi model, precision, recall, dan F1-score menggunakan confusion matrix dan classification report.

## Dataset

Dataset yang digunakan merupakan data teks berlabel sentimen (positif dan negatif). Data dibersihkan dan digunakan untuk melatih serta menguji performa model.
