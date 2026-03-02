# Rangkuman: Sistem Persamaan Linear

Berdasarkan materi komputasi aljabar linear, berikut adalah rangkuman mengenai konsep **Sistem Persamaan Linear**:

---

## 1. Definisi Persamaan Linear

Sebuah persamaan linear dalam $n$ variabel ($x_1, x_2, \dots, x_n$) adalah persamaan yang dapat disederhanakan ke dalam bentuk baku:

$$a_1x_1 + a_2x_2 + \dots + a_nx_n = b$$

* **Homogen**: Persamaan disebut homogen jika konstanta $b = 0$.
* **Nonhomogen**: Persamaan disebut nonhomogen jika konstanta $b \neq 0$.
* **Nonlinear**: Persamaan yang tidak dapat disederhanakan ke bentuk baku (misal: terdapat variabel kuadrat $x^2$ atau fungsi $\sin$).

---

## 2. Sistem Persamaan Linear (SPL)

Sistem persamaan linear merupakan himpunan atau kumpulan dari beberapa persamaan linear. 

* Sistem ini dikatakan **homogen** apabila seluruh persamaan di dalamnya adalah persamaan homogen. 
* Penulisan matematis menggunakan indeks ganda $a_{ij}$, di mana $i$ menunjukkan posisi baris dan $j$ menunjukkan variabel ke-$j$.

---

## 3. Solusi Sistem Persamaan Linear

Terdapat tiga kemungkinan himpunan solusi untuk sistem linear:

1.  **Tidak ada solusi**: Sistem diklasifikasikan sebagai **tidak konsisten**.
2.  **Solusi tunggal**: Sistem diklasifikasikan sebagai **konsisten**.
3.  **Tak hingga banyak solusi**: Sistem diklasifikasikan sebagai **konsisten**.

---

## 4. Representasi Matriks

Sistem persamaan linear dapat direpresentasikan secara ringkas dengan notasi $\mathcal{LS}(A, \mathbf{b})$:

* **$A$**: Matriks Koefisien yang berisi nilai koefisien variabel.
* **$\mathbf{b}$**: Vektor Konstanta yang berisi nilai dari ruas kanan persamaan.

---

## 5. Matriks Augmentasi (*Augmented Matrix*)

Untuk mempermudah perhitungan, kita menggunakan matriks augmentasi $[A \mid \mathbf{b}]$. Bentuknya dalam LaTeX adalah sebagai berikut:

$$
\left[
\begin{array}{cccc|c}
a_{11} & a_{12} & \dots & a_{1n} & b_1 \\
a_{21} & a_{22} & \dots & a_{2n} & b_2 \\
\vdots & \vdots & \ddots & \vdots & \vdots \\
a_{m1} & a_{m2} & \dots & a_{mn} & b_m
\end{array}
\right]
$$
