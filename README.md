# drowsiness-detection
Detecting Drowsiness with Machine Learning

## Pendahuluan

Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat mendeteksi tanda-tanda kantuk pada pengemudi berdasarkan gambar wajah. Kantuk dapat menyebabkan pengemudi menjadi tidak fokus dan berisiko menyebabkan kecelakaan. Dengan mengidentifikasi tanda-tanda kantuk, kita dapat memberikan peringatan dini kepada pengemudi untuk mengurangi risiko kecelakaan.

## Tahap 1: Pemahaman Masalah

Tahap ini melibatkan pemahaman mendalam tentang masalah yang ingin dipecahkan. Dalam hal ini, kita ingin mendeteksi tanda-tanda kantuk pada pengemudi berdasarkan gambar wajah mereka.

## Tahap 2: Pengumpulan Data

Dataset yang digunakan berasal dari [Drowsiness Dataset](https://www.kaggle.com/dheerajperumandla/drowsiness-dataset) di Kaggle. Dataset ini mencakup gambar wajah pengemudi dengan berbagai kondisi mata tertutup, mata terbuka, menguap, dan tidak menguap.

## Tahap 3: Persiapan Data

Pada tahap ini, kita memuat dataset dari Google Drive dan melakukan konversi gambar ke dalam format grayscale. Selain itu, kita juga membagi dataset menjadi gambar mata tertutup dan mata terbuka. Selanjutnya, kita mengubah nilai piksel menjadi rentang [0, 1] untuk normalisasi.

## Tahap 4: Pemodelan

Kami menggunakan Convolutional Neural Network (CNN) sebagai model untuk mendeteksi kantuk. CNN adalah pilihan yang baik karena kemampuannya dalam mengenali pola-pola visual dalam gambar.

## Tahap 5: Evaluasi

Metrik evaluasi yang digunakan adalah akurasi, precision, recall, dan F1-score. Model dievaluasi dengan menggunakan data uji yang tidak pernah dilihat sebelumnya.

## Kesimpulan

Melalui proyek ini, kami berhasil mengembangkan model deteksi kantuk yang mampu mengenali tanda-tanda visual kantuk pada pengemudi. Dengan akurasi yang baik, model ini dapat memberikan peringatan dini kepada pengemudi yang mengantuk dan dengan demikian meningkatkan keselamatan di jalan raya.

**Referensi**:
- [Drowsiness Dataset](https://www.kaggle.com/dheerajperumandla/drowsiness-dataset)
- [Understanding Convolutional Neural Networks](https://towardsdatascience.com/understanding-convolutional-neural-networks-through-visualizations-7f03404501b2)
- [Evaluation Metrics for Classification](https://towardsdatascience.com/understanding-evaluation-metrics-for-classification-models-e7723c5060d6)

