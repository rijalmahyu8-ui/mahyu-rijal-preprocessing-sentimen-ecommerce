# Preprocessing Sentimen Ulasan E-Commerce

## Identitas Mahasiswa
- **Nama:** Mahyu Rijal
- **NIM:** 25146025

## Deskripsi
Proyek ini melakukan preprocessing teks pada dataset ulasan produk e-commerce berbahasa Indonesia dari Hugging Face. Tahapan meliputi case folding, cleaning, tokenisasi, stopword removal, dan stemming.

## Dataset
https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment

Dataset yang digunakan pada notebook memiliki kolom `review`, `translate`, dan `sentimen`. Label sentimen: 0 = negatif dan 1 = positif. Jumlah baris dan distribusi kelas dihitung langsung saat notebook dijalankan.

## File
- `preprocessing_sentimen_ecommerce.ipynb` — notebook pemuatan data, eksplorasi, distribusi label, dan preprocessing.
- `hasil_preprocessing_sentimen.csv` — hasil dataset setelah preprocessing.
- `README.md` — dokumentasi proyek dan identitas mahasiswa.

## Cara Menjalankan
1. Buka notebook di Google Colab atau Jupyter Notebook.
2. Jalankan sel instalasi library.
3. Jalankan seluruh sel secara berurutan.
4. Distribusi label dan 10 contoh preprocessing akan dihasilkan langsung dari dataset.

## Library
`datasets`, `pandas`, `nltk`, `Sastrawi`, `matplotlib`

## Hasil
Notebook menghasilkan kolom baru `review_preprocessed` dan menyimpan hasil ke `hasil_preprocessing_sentimen.csv`.
