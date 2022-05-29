# P2_Probstat_F_05111940000223
Naufal Fabian W 05111940000223  Probabilitas dan Statistika F



## No 1

- A.

Carilah Standar Deviasi dari data selisih pasangan pengamatan tabel diatas.

Mencari standar deviasi dari selisih data pada tabel dengan `sd`
![Screenshot 2022-05-29 181111](https://user-images.githubusercontent.com/85657973/170865045-d1e89c59-28dd-4c56-8f52-901757722dd3.png)


- B.

Carilah nilai t (p-value)

Mencari nilai t(p-value) dengan `t.test`
![Screenshot 2022-05-29 181134](https://user-images.githubusercontent.com/85657973/170865055-3b2d0b16-3df0-4b9b-a1e9-5d245639227e.png)
nilai t = 7.6525

- C.

Tentukanlah apakah terdapat pengaruh yang signifikan secara statistika dalam hal kadar saturasi oksigen , sebelum dan sesudah melakukan aktivitas 𝐴 jika diketahui tingkat signifikansi 𝛼 = 5% serta H0 : “tidak ada pengaruh yang signifikan secara statistika dalam hal kadar saturasi oksigen , sebelum dan sesudah melakukan aktivitas 𝐴”

Hipotesis nol ditolak , Hipotesis alternatif diterima. terdapat pengaruh yang signifikan secara statistika dalam hal kadar saturasi oksigen , sebelum dan sesudah mengkonsumsi obat A pada tingkat signifikasi 5%.


## No 2

- A.

Apakah Anda setuju dengan klaim tersebut?

Setuju

- B.

Jelaskan maksud dari output yang dihasilkan

Mencari output dengan `zsum.test()`

![Screenshot 2022-05-29 183032](https://user-images.githubusercontent.com/85657973/170865748-72f545d2-f7ed-464b-8ef2-f1f10d7bfbb5.png)
![Screenshot 2022-05-29 183045](https://user-images.githubusercontent.com/85657973/170865753-61529c32-d0e5-4f7c-9779-586aa6e13137.png)

- C.

Buatlah kesimpulan berdasarkan P-Value yang dihasilkan!

Setelah dihitung, didapat bahwa z = 8.97 , μ > 20, 000 kilometers ,  dan P-value < 0.001.
Dapat disimpulkan bahwa mobil dikemudikan rata rata lebih dari 20.000 Kilometer per tahun.

## No 3

- A.
- B.
- C.

## No 4

- A.

Import table 

![Screenshot 2022-05-29 211546](https://user-images.githubusercontent.com/85657973/170873832-9ca8bbe6-f6f2-4dca-8a8e-39d404b33869.png)

Mengkategorikan grup

![Screenshot 2022-05-29 211612](https://user-images.githubusercontent.com/85657973/170873994-5dd2347b-e6a2-4922-a2ee-666ddc2c214b.png)

Plot kuantil normal

Group1

![Screenshot 2022-05-29 212248](https://user-images.githubusercontent.com/85657973/170874102-a6ba3006-d9d3-4687-a98a-6b1e3911a8cb.png)
![Screenshot 2022-05-29 212259](https://user-images.githubusercontent.com/85657973/170874104-299d9ac5-ebf3-4122-9693-3678ffdaf2bd.png)

Group2

![Screenshot 2022-05-29 212356](https://user-images.githubusercontent.com/85657973/170874147-f4251168-162f-4869-b5e2-57f76d2a568f.png)
![Screenshot 2022-05-29 212408](https://user-images.githubusercontent.com/85657973/170874156-4099c478-bb24-4829-a152-c4a877b123d7.png)

Group3

![Screenshot 2022-05-29 212513](https://user-images.githubusercontent.com/85657973/170874219-bb440f22-38a3-41fa-ae86-863ea1d7f8fa.png)
![Screenshot 2022-05-29 212524](https://user-images.githubusercontent.com/85657973/170874227-53cccd86-826f-455f-860c-8230f7fc3c29.png)

- B.

Carilah atau periksalah Homogeneity of variances nya , Berapa nilai p yang didapatkan? , Apa hipotesis dan kesimpulan yang dapat diambil ?

Mencari homogenity of variances menggunakan `bartlett.test()`

![Screenshot 2022-05-29 212829](https://user-images.githubusercontent.com/85657973/170874525-0969bb49-1554-4177-84fa-5cedd512a986.png)

Nilai p dari bartlett.test 0.8054. Kesimpulannya variance dari ketiga grup mirip

- C.

Untuk uji ANOVA (satu arah), buatlah model linier dengan Panjang versus Grup dan beri nama model tersebut model 1.

![Screenshot 2022-05-29 214114](https://user-images.githubusercontent.com/85657973/170875442-768b350e-d90f-4c89-9311-011098a53538.png)

![Screenshot 2022-05-29 214554](https://user-images.githubusercontent.com/85657973/170875447-d86123b5-e11f-4c13-b561-27fc28e85eed.png)

- D.
- 
Dari Hasil Poin C , Berapakah nilai-p ? , Apa yang dapat Anda simpulkan dari H0?

Nilai p adalah 0.0013 yang dimana < 0.05. Kesimpulannya hipotesis nol ditolak.

- E.

Verifikasilah jawaban model 1 dengan Post-hoc test Tukey HSD, dari nilai pyang didapatkan apakah satu jenis kucing lebih panjang dari yang lain?

Memverifikasi dengan menggunakan `TurkeyHSD()`

![Screenshot 2022-05-29 215744](https://user-images.githubusercontent.com/85657973/170876010-f7bb3514-8206-4f93-95c8-36e4d543fa21.png)

- F.

Visualisasikan data dengan ggplot2

Memvisualisasi dengan menggunakan `ggplot2`

![Screenshot 2022-05-29 215910](https://user-images.githubusercontent.com/85657973/170876152-e2bd2c8b-ec22-4f88-b299-9a25f287aaaf.png)

![Screenshot 2022-05-29 220226](https://user-images.githubusercontent.com/85657973/170876227-f10bbd0e-e000-4ae7-8134-0455fe7f01e4.png)



## No 5

- A.
- B.
- C.
- D.
- E.


