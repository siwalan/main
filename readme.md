# Scrapper Sitasi Google Scholar
## Google Scholar Citation Scrapper

### IND
##### Latar Belakang 

Borag Akreditasi BAN-PT yang baru (AIPT 4.0) meminta bagi setiap Program Studi untuk mencantumkan **outcome** dari hasil penelitian sivitas akademika. Mendata/mencantumkan jurnal yang dihasilkan saja sudah tidak cukup, tetapi dampak dari jurnal dari jurnal tersebut perlu dilaporkan. Dampak dari jurnal tersebut diukur dari jumlah sitasi yang dimiliki jurnal tersebut. Sebagian besar Universitas tidak memiliki data ini karena untuk mendapatkan jumlah sitasi, perlu dilakukan proses *cross-reference* antar jurnal dalam jumlah besar. Untuk melakukan hal tersebut bukanlah suatu hal yang mudah, sehingga jalan yang masih memungkinkan adalah mengambil data sitasi dari *provider* data yang sudah ada seperti SINTA, Scopus, WOS, dan Google Scholar. Dalam Google Scholar, ada data total sitasi suatu jurnal dan data sitasi per tahun jurnal tersebut.

Sampai sekarang (Des 2019), Google Scholar tidak menyediakan API sehingga proses pengambilan data dari Google Scholar perlu dilakukan secara manual. Mengingat jumlah dosen dan karya tulis ilmiah dosen yang begitu besar, untuk beberapa Prodi pengunduhan data secara manual bukanlah suatu opsi. Scrapper ini dapat membantu bagi Prodi yang perlu mengambil data sitasi dalam jumlah besar. Selain dosen Prodi, scrapper ini dapat digunakan oleh peneliti yang tertarik untuk mengolah data sitasi penelitian nya secara lebih mendalam.

##### Cara Penggunaan

NOTE: Anda dianjurkan menggunakan versi .IPYNB (Jupyter Lab), versi .py belum pernah dicoba dan disediakan sebagai as-is saja. 
1. Ambil Google Scholar ID anda dari Profile Google Scholar anda

Contoh: Dalam link ini, yang merupakan Google Scholar ID adalah **qc6CJjYAAAAJ**
> https://scholar.google.com/citations?user=qc6CJjYAAAAJ&hl=en
2. Masukan Google Scholar ID anda dalam suatu * *file* * CSV (dalam repo ini, *file* nya memiliki nama dosen.csv, pastikan ada dua kolom dalam * *file* * tersebut. Nama dan Scholar-ID)
3. Jalankan script
4. Setelah script selesai, maka data sitasi akan diexport ke suatu *file* .xlsx

##### Catatan

Apabila anda melakukan request terlalu banyak, maka Google akan memberikan ada Respones 429. Ini berarti Google Scholar melakukan * *IP-Block* * akan komputer anda. Untuk mengatasi hal ini silahkan menunggu waktu sampai anda di bebaskan dari * *IP-Block* * Google atau ganti IP anda.
