NIM : 2201010582    NAMA :  I Gusti Ngurah Agung Surya Pradiva

Project : Aplikasi Kasir Toko Agung

Deskripsi :  saya membuat aplikasi kasir diamana aplikasi tersebut bisa mencari nama barang dan tau harga barang setelah itu dapat menghitung jumlah barang yang di beli customer dan bisa membatalkan jika ada salah ketik dan jika membayar dengan uang yang kurang maka muncul tulisan uang anda kurang jika membayar lebih akan muncul nominal kembaliannya dan jika selesai transaksi langsung bisa klik keluar  

disini saya menggunakan metode oop inheritance Kelas formutama mewarisi dari kelas javax.swing.JFrame, sehingga mendapatkan semua properti dan metode dari JFrame.   contohnya:

java

public class formutama extends javax.swing.JFrame {

    // Kelas ini mewarisi properti dan metode dari JFrame

}

dan ada kelas  Encapsulation 

Kelas formutama juga menunjukkan enkapsulasi dengan menyembunyikan data dan operasi di dalam kelasnya. Variabel-variabel GUI seperti namabarang, jumlahharga, hargabarang, dan sebagainya, dideklarasikan dalam kelas dan hanya dapat diakses serta dimodifikasi melalui metode dalam kelas tersebut.

contohnya :

java

private javax.swing.JButton batal;

private javax.swing.JButton bayar;

private javax.swing.JTextField hargabarang;

private javax.swing.JComboBox<String> namabarang;

