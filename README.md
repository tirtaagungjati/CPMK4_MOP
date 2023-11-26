# CPMK4_MOP

Terdapat 4 Permasalahan Kasus Yang Kita Angkat:
1. ZDT1
2. ZDT2
3. Himmelblau
4. Masalah optimisasi geometri

Dimana Permasalahan Yang diangkat kecuali nomor 4 adalah benchmark suatu algoritma dalam memecahkan permasalahan MOP. Permasalahan 1-3 terdapat pada file jupyter cpmk4.ipynb dan cpmk4_versi2.ipynb
Didapatkan Kesimpulan Dimana 
1. Algoritma Pareto Archived Evolution Strategy yang dibuat masih belum bisa mengalahkan algoritma FSGA, NSGA-II, SPEA-2 PADA PERMASALAHAN ZDT1
2. Algoritma Pareto Archived Evolution Strategy yang dibuat masih bisa lebih baik daripada algoritma NSGA-II dab SPEA-2 akan tetapi masih belum bisa mengalahkan algoritma FSGA PADA PERMASALAHAN ZDT2
Berikut papernya :  https://www.researchgate.net/publication/224309321_A_Multiobjective_Evolutionary-Simplex_Hybrid_Approach_for_the_Optimization_of_Differential_Equation_Models_of_Gene_Networks 

Permasalahan Ke 4
Suatu arsitek ingin merancang suatu bangunan, misalnya suatu piramida, dengan tujuan untuk memaksimumkan volume dan meminimumkan luas permukaan. Setiap aspek bangunan memiliki beberapa parameter yang dapat diubah, misalnya tinggi, panjang, dan lebar. Masalah ini dapat dimodelkan sebagai suatu masalah optimisasi nonlinier dengan dua fungsi tujuan dan sejumlah kendala yang berkaitan dengan batasan dimensi dan estetika
Misalkan ada 1 parameter yang dapat diubah, yaitu panjang sisi alas (L). Fungsi tujuan dan kendala dapat diasumsikan sebagai berikut:
![image](https://github.com/tirtaagungjati/CPMK4_MOP/assets/65837182/ae2a59a5-ca30-4ada-8f4c-5871f4687ff8)
Di mana f1​(x) adalah fungsi yang mengukur volume, f2​(x) adalah fungsi yang mengukur luas permukaan, dan L adalah panjang sisi alas piramida

Didapatkan Kesimpulan Pada Problem ke 4 menggunakan Algoritma Pareto Archived Evolution Strategy mendapatkan hasil dimana 
Jika grafik F1(x) dan F2(x) menunjukkan garis lurus (grafik linear), ini berarti bahwa ketika panjang sisi alas piramida diperbesar:
1. Volume piramida (F1(x)) dan luas permukaannya (F2(x)) meningkat secara seimbang dan proporsional.
2. Artinya, ketika sisi alas piramida diperbesar sebesar jumlah tertentu, volume dan luas permukaannya juga akan bertambah sebesar jumlah yang proporsional.

Ini menunjukkan hubungan langsung di mana setiap peningkatan panjang sisi alas piramida akan memberikan peningkatan volume dan luas permukaan piramida dalam jumlah yang sama.
Dalam kata lain, jika grafiknya linear, maka ketika Anda perbesar ukuran sisi alas piramida, baik volumenya maupun luas permukaannya akan bertambah dengan cara yang sama dan teratur.
