## BAB I
**PENDAHULUAN** <br>
&emsp;**1.1.**	**Tujuan**<br>
&emsp;&emsp;Dokumen ini akan menyajikan deskripsi rinci tentang aplikasi yang akan dikembangkan. Dokumen akan menjelaskan mengenai spesifikasi pada aplikasi tersebut seperti fitur sistem, antarmuka sistem, sistem apa yang akan dilakukan, apa saja kendala pada saat aplikasi beroperasi, dana bagaimana system akan bereaksi pada saat sedang digunakan oleh pemakai atau user.<br><br>

&emsp;**1.2.**	**Lingkup**<br>
&emsp;&emsp;Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi yang kami buat. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis website yang memilih beberapa fasilitas yang ada yaitu:<br>
&emsp;&emsp;&emsp;1.	Admin untuk mengelola data CRUD (Create, Read, Update, Delete) yang ada pada fitur- fitur aplikasi seperti input data produk, mendaftarkan akun kasir serta memonitoring laporan keuangan dan keuntungan perusahaan.<br>
&emsp;&emsp;&emsp;2.	Kasir sebagai tempat perhitungan pada transaksi pembelian yang dilakukan oleh pelanggan dan dapat memonitoring hasil pendapatan pada hari ini.<br>
&emsp;&emsp;&emsp;3.	Pengunjung dapat melihat data berupa informasi perusahaan dan data produk yang ada di website.<br>
&emsp;&emsp;&emsp;4.	Pelanggan dapat melakukan transaksi pembelian pada aplikasi setelah melakukan login.<br>
<br>
&emsp;**1.3.**	**Definisi, akronim, singkatan**<br>
&emsp;&emsp;Adapun definisi dari dokumen tersebut adalah:<br>
<table width="538">
<tbody>
<tr>
<td width="37">
<p><strong>No</strong></p>
</td>
<td width="189">
<p><strong>Akronim</strong></p>
</td>
<td width="312">
<p><strong>Singkatan</strong></p>
</td>
</tr>
<tr>
<td width="37">
<p><strong>1.</strong></p>
</td>
<td width="189">
<p>SPMP</p>
</td>
<td width="312">
<p>Software Project Management Plan</p>
</td>
</tr>
<tr>
<td width="37">
<p><strong>2.</strong></p>
</td>
<td width="189">
<p>SRS</p>
</td>
<td width="312">
<p>Software Requirements Specifications</p>
</td>
</tr>
<tr>
<td width="37">
<p><strong>3.</strong></p>
</td>
<td width="189">
<p>SDD</p>
</td>
<td width="312">
<p>Software Design Document</p>
</td>
</tr>
<tr>
<td width="37">
<p><strong>4.</strong></p>
</td>
<td width="189">
<p>DFD</p>
</td>
<td width="312">
<p>Data Flow Diagram</p>
</td>
</tr>
<tr>
<td width="37">
<p><strong>5.</strong></p>
</td>
<td width="189">
<p>IEEE</p>
</td>
<td width="312">
<p>International Institute of Electronic and Electrical Engineers</p>
</td>
</tr>
<tr>
<td width="37">
<p><strong>6.</strong></p>
</td>
<td width="189">
<p>CRUD</p>
</td>
<td width="312">
<p>Create, Read, Update, dan Delete</p>
</td>
</tr>
</tbody>
</table>
<br>
<br>

&emsp;**1.4.**	**Referensi**<br>
&emsp;&emsp;IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications.<br>
<br>
&emsp;**1.5.**	**Overview**<br>
&emsp;&emsp;Penulisan dokumen SRS ini dibagi menjadi beberapa bab sebagai berikut:<br>
&emsp;&emsp;&emsp;BAB I berisi pendahuluan, menjelaskan mengenai tujuan pembuatan dokumen SRS, lingkup, definisi (akronim, atau singkatan), referensi, dan Overview.<br>
&emsp;&emsp;&emsp;BAB II menjelaskan keseluruhan deskripsi dari Aplikasi. Deskripsi umum tersebut memberikan gambaran lengkap mengenai semua fungsi yang akan dilakukan oleh sistem.<br>
&emsp;&emsp;&emsp;BAB III berisi penjelasan detail dari  masing-masing kebutuhan lain yang spesifik.<br>
&emsp;&emsp;&emsp;BAB IV berisikan tentang uraian mengenai informasi pendukung dalam pembuatan proyek Aplikasi ini.<br>

##3. PROSES MANAJERIAL

**3.1. Performa**

- Respon program kurang 30 detik.
- Berjalan pada browser apapun.

**3.2. Keamanan Aplikasi**

- Validasi username dan password harus sesuai dengan yang didaftarkan sehingga tidak terjadi kesalahan login pada aplikasi.


##4. INFORMASI PENDUKUNG

Informasi yang kami dapatkan, yaitu dari beberapa situs website, jurnal tugas akhir, dan mitra (PD Sri Tanjung).

<p><strong>BAB II</strong></p>
<p><strong>ORGANISASI PROYEK</strong></p>
<p>Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu (PD Sri Tanjung) berbasis Website ini merupakan salah satu jenis perangkat lunak yang digunakan untuk membantu proses pengelolaan data dan pencatatan informasi yang terkait dengan informasi penjualan kerupuk pada PD Sri Tanjung. Yang mana sebelumnya pada perusahaan daerah ini proses pengelolaan data masih dilakukan secara manual, dimana pegawai harus mencatat sendiri apa-apa yang berkaitan dengan perusahaan tanpa menggunakan bantuan alat atau software apapun. Hal tersebut dinilai kurang efisien, sebab dapat menghabiskan banyak waktu hanya untuk melakukan pendataan saja. Untuk itu, kami membuat aplikasi ini untuk mempermudah baik itu pegawai maupun client yang ingin melihat detail produk yang ada hanya dengan bermodalkan gadget saja.</p>
<p>Pada proyek ini dibuat suatu system dimana pengisian data informasi mengenai kerupuk dilakukan oleh admin melalui PC atau Laptop. Sebelum dilakukannya pengisian data, dilakukan terlebih dahulu proses pengumpulan data ketika survey dilakukan. Tetapi kemudian untuk selanjutnya update data informasi akan dilakukan oleh mitra. Aplikasi ini dibangun menggunakan Bahasa Pemrograman PHP dan Framework Bootstrap serta Laravel. Sedangkan database mengenai informasi travelnya kami menggunakan MySQL.</p>
<p><strong>2.1. Persfektif Produk</strong></p>
<p>Aplikasi Pendataan Terpusat dan Informasi Produk Usaha Kerupuk Indramayu (PD Sri Tanjung) adalah perangkat lunak yang digunakan untuk membantu proses pengelolaan data dan pencatatan informasi yang terkait dengan informasi penjualan kerupuk pada PD Sri Tanjung. Selain itu aplikasi inipun digunakan untuk melakukan transaksi secara online melalui website penjualan.</p>
<p><strong>2.1.1. Antarmuka Sistem</strong></p>
<p>Dalam penggunaan, pengguna berinteraksi langsung dengan aplikasi melalui PC/Laptop.</p>
<p><strong>&nbsp;</strong></p>
<p><strong>2.1.2. Antarmuka pengguna</strong></p>
<p>Aplikasi ini menggunakan antarmuka berbasis website. Dimana antarmuka website ini digunakan oleh seluruh pengguna.</p>
<p>&nbsp;</p>
<p><strong>2.1.3. Antarmuka perangkat keras</strong></p>
<ul>
<li>Laptop</li>
<li>Processor Core i5 or higher</li>
<li>Penyimpanan(Hardisk) Minimal 4 GB free space</li>
<li>Smartphone minimal android Jelly Bean or higher</li>
<li>Monitor resolusi 1240 x 768 colors 5</li>
<li>Ke<strong>y</strong>board dan mouse compatible with windows</li>
</ul>
<p>&nbsp;</p>
<p><strong>2.1.4. Antarmuka perangkat lunak</strong></p>
<ul>
<li>Windows 7 or higher</li>
<li>Corel Draw X7</li>
<li>Laragon</li>
<li>Balsamiq Mockups 3</li>
<li>Sublime Text 3 atau Dreamweaver</li>
</ul>
<p>&nbsp;</p>
<p><strong>2.1.5. Antarmuka komunikasi</strong></p>
<ul>
<li>Paket Data</li>
<li>Wifi</li>
<li>Modem</li>
<li>Smartphone</li>
</ul>
<p>&nbsp;</p>
<p><strong>2.1.6. Batasan Memori</strong></p>
<ul>
<li>RAM yang kami gunakan adalah minimal 4 gb.</li>
<li>Memori yang dibutuhkan aplikasi minimal 50 mb.</li>
</ul>
<p><strong>&nbsp;</strong></p>
<p><strong>2.1.7. Operasi-operasi</strong></p>
<ul>
<li>Input data kasir</li>
<li>Input data kerupuk</li>
<li>Input pesanan</li>
<li>Update data admin</li>
<li>Update data kasir</li>
<li>Update data kerupuk</li>
<li>Tampilan hasil penjualan harian</li>
<li>Laporan hasil penjualan</li>
</ul>
<p>&nbsp;</p>
<p><strong>2.1.8. Kebutuhan Adaptasi</strong></p>
<p>Kebutuhan adaptasi yang diperlukan pada saat pengembangan aplikasi dengan menggunakan fungsi update data agar memudahkan admin dalam mengkoreksi pengetikan yang salah.</p>
<p><strong>&nbsp;</strong></p>
<p><strong>2.2. Fungsi-fungsi Produk</strong></p>
<ul>
<li>Memudahkan pelayanan dalam mencatat pesanan pelanggan.</li>
<li>Memberi tahu pelanggan kerupuk mana yang habis dan yang tidak.</li>
<li>Memudahkan pemilik perusahaan untuk melihat pendapatan maupun laporan keuangan perusahaan.</li>
</ul>
<p>&nbsp;</p>
<p><strong>2.3. Karakteristik Pengguna</strong></p>
<ul>
<li>Pengguna mampu membaca dan menulis.</li>
<li>Pengguna mengerti cara menggunakan smartphone dengan sistem operasi android.</li>
<li>Pengguna mengerti cara menggunakan PC dengan sistem operasi setidaknya windows.</li>
<li>Mengerti cara menggunakan browser pada PC.</li>
</ul>
<p><strong>&nbsp;</strong></p>
<p><strong>2.4. Batasan-batasan&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong></p>
<ul>
<li>Berjalan pada platform website</li>
<li>Sementara ini aplikasi ini hanya untuk PD Sri Tanjung Indramayu</li>
<li>Aplikasi ini tidak untuk layanan pesan antar</li>
</ul>
<p><strong>&nbsp;</strong></p>
<p><strong>2.5. Asumsi-asumsi dan Keterkaitan</strong></p>
<p>Aplikasi ini dapat dikembangkan lagi dengan menambah banyak pengguna, dan penambahan super admin untuk konfirmasi perusahaan mana saja yang boleh menggunakan aplikasi ini. Sehingga aplikasi ini dapat digunakan oleh banyak perusahaan yang ingin menggunakan aplikasi ini.</p>
<p><strong>&nbsp;</strong></p>
<p><strong>2.6. Kebutuhan-kebutuhan Penyeimbang</strong></p>
<ul>
<li>Customer Requirements</li>
</ul>
<p>Customer Requirements adalah analisis yang dilakukan terhadap pelanggan agar dapat mengetahui apa saja kebutuhan pelanggan sehingga pengembang dapat membuat sistem yang sesuai dengan kebutuhan pelanggan.</p>
<ul>
<li>Detil Requirements</li>
</ul>
<p>Detil Requirements adalah suatu analisis yang terdiri dari properti dan fungsionalitas spesifik yang diekspresikan dalam bentuk yang detail.</p>