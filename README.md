# **Riset Informatika ( C )**

Nama : Novandi Kevin Pratama
NPM : 20081010005

## Table of Content
- [Topik Penelitian](#topik-penelitian)
  1. [Segmentasi Vocal dan Instrumen Musik dengan Mel-Frequency Cepstral Coefficient dan K-Means Clustering](#topik-1-segmentasi-vocal-dan-instrumen-musik-dengan-mel-frequency-cepstral-coefficient-dan-k-means-clustering)
     - [Persoalan Praktis](#persoalan-praktis)
     - [Research Questions](#research-questions)
     - [Teori Yang Berkaitan](#teori-yang-berkaitan)
  2. [Klasifikasi Diabetes Resinopati dengan Gabor Filter dan Support Vector Machine](#topik-2-klasifikasi-diabetes-resinopati-dengan-gabor-filter-dan-support-vector-machine)
     - [Persoalan Praktis](#persoalan-praktis-1)
     - [Research Questions](#research-questions-1)
     - [Teori Yang Berkaitan](#teori-yang-berkaitan-1)

## Topik Penelitian

1. Segmentasi Vocal dan Instrumen Musik dengan Mel-Frequency Cepstral Coefficient dan K-Means Clustering
2. Klasifikasi Diabetes Resinopati dengan Gabor Filter dan Support Vector Machine

## Topik 1. Segmentasi Vocal dan Instrumen Musik dengan Mel-Frequency Cepstral Coefficient dan K-Means Clustering

Penelitian terkait dengan pengolahan sinyal audio, khususnya analisis musik. Penelitian ini bertujuan untuk membagi sinyal audio menjadi segmen-segmen yang terdiri dari vokal dan instrumen musik

### Persoalan Praktis

1. Kualitas data

Kualitas data audio dapat dipengaruhi oleh berbagai faktor, seperti kondisi perekaman, jenis mikrofon yang digunakan, dan tingkat kebisingan lingkungan. Data audio yang berkualitas buruk dapat menyebabkan hasil segmentasi yang tidak akurat atau tidak konsisten. Misalnya, data audio yang berisi kebisingan latar belakang yang tinggi dapat menyebabkan algoritma K-Means Clustering salah mengkategorikan noise sebagai vokal atau instrumen musik.

1. Pilihan parameter

MFCC dan K-Means Clustering memiliki berbagai parameter yang dapat disesuaikan untuk meningkatkan akurasi segmentasi. Parameter-parameter ini dapat mencakup jumlah fitur MFCC, ukuran jendela FFT, dan jumlah cluster K-Means. Pemilihan parameter yang tidak tepat dapat menyebabkan hasil segmentasi yang tidak akurat. Misalnya, pemilihan jumlah fitur MFCC yang terlalu kecil dapat menyebabkan algoritma MFCC kehilangan informasi penting yang dapat digunakan untuk membedakan vokal dan instrumen musik.

### Research Questions

1. Bagaimana cara meningkatkan akurasi segmentasi vocal dan instrumen musik dengan MFCC dan K-Means Clustering?
2. Bagaimana cara mengevaluasi akurasi segmentasi vocal dan instrumen musik dengan MFCC dan K-Means Clustering?
3. Bagaimana cara mengatasi data yang tidak lengkap atau tidak seimbang dalam segmentasi vocal dan instrumen musik?
4. Bagaimana cara mengatasi data yang bervariasi dalam segmentasi vocal dan instrumen musik?

### Teori Yang Berkaitan

1. MFCC (Mel-Frequency Cepstral Coefficient)

MFCC adalah singkatan dari Mel-Frequency Cepstral Coefficient. MFCC adalah fitur ekstraksi yang digunakan untuk mewakili karakteristik frekuensi sinyal audio. MFCC dihitung dengan transformasi Fourier mel, yang merupakan transformasi Fourier yang dimodifikasi untuk meniru cara telinga manusia mendengar. MFCC terdiri dari sejumlah koefisien, yang masing-masing mewakili karakteristik frekuensi tertentu.

1. K Means Clustering

K Means Clustering adalah algoritma clustering yang digunakan untuk mengelompokkan data ke dalam sejumlah cluster. K Means Clustering bekerja dengan cara memilih sejumlah titik pusat cluster (centroid) secara acak. Kemudian, data dikelompokkan ke dalam cluster yang terdekat dengan centroidnya. Proses ini diulangi hingga centroid tidak berubah lagi.

1. Clustering

Clustering adalah teknik pembelajaran mesin yang digunakan untuk mengelompokkan data ke dalam sejumlah cluster. Data dalam satu cluster memiliki karakteristik yang mirip, sedangkan data dalam cluster yang berbeda memiliki karakteristik yang berbeda.

1. Segmentasi

Segmentasi adalah teknik pengolahan sinyal yang digunakan untuk membagi sinyal menjadi segmen-segmen yang lebih kecil. Segmentasi dapat digunakan untuk berbagai aplikasi, seperti analisis musik, pemrosesan bahasa alami, dan sintesis musik.

## Topik 2. Klasifikasi Diabetes Resinopati dengan Gabor Filter dan Support Vector Machine

### Persoalan Praktis

1. Kualitas data

Kualitas data retina dapat dipengaruhi oleh berbagai faktor, seperti kualitas kamera, kondisi pasien, dan kondisi pencahayaan. Data retina yang berkualitas buruk dapat menyebabkan hasil klasifikasi yang tidak akurat atau tidak konsisten. Misalnya, data retina yang berisi noise atau artefak dapat menyebabkan algoritma Support Vector Machine salah mengkategorikan drusen sebagai edema.

1. Pilihan parameter

Support Vector Machine memiliki berbagai parameter yang dapat disesuaikan untuk meningkatkan akurasi klasifikasi. Parameter-parameter ini dapat kernel Support Vector Machine, dan parameter C. Pemilihan parameter yang tidak tepat dapat menyebabkan hasil klasifikasi yang tidak akurat.

1. Privasi data

Penelitian tentang klasifikasi diabetes retinopati harus memperhatikan etika, seperti privasi pasien dan keamanan data. Hal ini penting untuk melindungi privasi pasien dan mencegah penyalahgunaan data.

### Research Questions

1. Bagaimana cara meningkatkan kualitas data retina untuk klasifikasi diabetes retinopati?
2. Bagaimana cara memilih parameter Support Vector Machine yang optimal untuk klasifikasi diabetes retinopati?
3. Bagaimana cara mengevaluasi akurasi klasifikasi dengan berbagai parameter Support Vector Machine?
4. Bagaimana cara melindungi privasi pasien saat menggunakan data retina untuk penelitian?

### Teori Yang Berkaitan

1. Diabetes resinopati

Diabetes resinopati adalah komplikasi dari diabetes mellitus yang dapat menyebabkan kebutaan. Diabetes mellitus adalah penyakit kronis yang ditandai dengan kadar gula darah yang tinggi. Diabetes mellitus dapat menyebabkan kerusakan pada pembuluh darah, termasuk pembuluh darah di retina. Kerusakan pembuluh darah di retina dapat menyebabkan munculnya exudate, yaitu kumpulan cairan yang keluar dari pembuluh darah retina yang rusak. Exudate dapat terlihat sebagai bintik putih atau kuning pada citra fundus retina.

1. Klasifikasi

Klasifikasi adalah proses membagi data ke dalam dua atau lebih kelas. Kelas adalah kumpulan data yang memiliki karakteristik yang sama.

1. SVM (Support Vector Machine)

SVM (Support Vector Machine) adalah algoritma pembelajaran mesin yang dapat digunakan untuk klasifikasi, regresi, dan clustering. SVM bekerja dengan menemukan hyperplane yang memisahkan dua kelas data dengan margin yang paling besar. Hyperplane adalah garis atau bidang yang memisahkan dua atau lebih kelas data. Margin adalah jarak antara hyperplane dan titik-titik data yang paling dekat dengan hyperplane. SVM bertujuan untuk menemukan hyperplane dengan margin yang paling besar.

1. Gabor filter

Gabor filter adalah filter linier yang dapat digunakan untuk mengekstrak fitur tekstur dari citra. Gabor filter memiliki karakteristik frekuensi dan arah yang dapat digunakan untuk mendeteksi fitur-fitur tertentu dalam citra.
