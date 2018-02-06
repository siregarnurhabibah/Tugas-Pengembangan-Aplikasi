# Company Inventory 

## Identifikasi stakeholder
1.  Pemilik
2.  Karyawan (kasir)
3.  Kreditor
4.  Pemasok
5.  Pelanggan
6.  Pesaing

## Identifikasi tujuan proyek
	Penerapan aplikasi *Point of Sale* (POS) Nadipos pada *Global Store* membantu pendataan setiap transaksi secara lengkap dan detail. Selain itu, dapt digunakan untuk perhitungan persediaan barang, baik secara online/real-time, kita juga dapat mengubah harga jual dengan mudah dan mempersingkat proses transaksi dengan aman
## Functional Requirement
Fitur-fitur yang harus diimplementasikan pada aplikasi ini adalah:
1. Menerima orderan dan nomer member pada transaksi pembayaran.
2. Setiap nomer member yang terdaftar mendapatkan harga khusus
3. Mencetak faktur order yang menampilkan jumlah order, harga dan total pembayaran.
4. Mencatat jumlah uang yang ada pada cash register.
5. Setiap staff yang bertguas dalam setiap proses pembayaran telah tercataat dan terdaftar dalam semua transaksi.
### Flow Proses Bisnis
1. Pelanggan datang ke Global Store dan melakukan proses pemesanan terhadap staf di counter
2. Staf menginput nomer member (jika ada) dan daftar pemesanan ke sistem.
3. Pelanggan memilih metode pembayaran
4. Mencetak faktur order dan pembayaran
5. Pelanggan memproses pembayaran
6. Staff memberi uang kembalian(jika perlu).
7. Pelanggan menerima barang konsumsi.

## Design Solusi
* Needs
1. Aplikasi Point of Sales (POS) NADIPOS
	* identifikasi staf
	* input nomer member (harga member)
	* penetapan metode pembayaran
	* cetak faktur order
	* laporan transaksi
2. catatan jumlah uang pada cash register
	* Deposit (menambah uang ke cash register bukan melalui proses pembayaran)
	* withdrwal (mengambil dari cash register)
	* pergantian staf (cetak tanda serah terima)
	* laporan jumlah uang beserta transaksi

## Features

1. Aplikasi Point of Sales (POS)

	*User management

	Untuk login/logout dan identifikasi staff yang melakukan transaksi.

	*Fungsi untuk manajemen:

		- Menambahkan user baru
		- Menghapus/disable user (user tidak dapat login)
		- Mengganti password user (reset password)

2. Product management

* Untuk daftar produk yang dijual dan bisa diorder.

	- Menambahkan product baru
	- Mengupdate informasi product
	- Menghapus/mengnontaktifkan product

* Order and Payment

	- Menerima orderan dan menerima pembayaran.
	- Menerima pemesanan dari pelanggan
	- Menerima pembayaran dari pelanggan

* Report

	- Menampilkan daftar transaksi yang terjadi.
	- Catatan jumlah uang pada Cash Register

* User management

	Untuk login/logout dan identifikasi staff yang melakukan transaksi.

* Cash out/in

	Untuk melakukan deposit atau withdrawal dari cash register yang tidak berkaitan dengan transaksi penjualan.

* Ganti shift

	Proses pergantian staff kasir.

* Report

	Menampilkan jumlah uang dan transaksi.
	





