---
title: SocketOptionName
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan nama opsi socket untuk kelas Socket.
type: docs
weight: 248
url: /id/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Mendefinisikan nama opsi socket untuk kelas [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Debug | 1 | Merekam informasi debug. |
| AcceptConnection | 2 | Menunjukkan apakah socket mendengarkan koneksi masuk. |
| ReuseAddress | 4 | Menunjukkan apakah socket dapat diikat ke alamat yang sudah digunakan. |
| KeepAlive | 8 | Mengaktifkan paket 'Keep-Alive' untuk koneksi socket. |
| DontRoute | 16 | Menunjukkan apakah paket dikirim langsung ke alamat antarmuka. |
| Broadcast | 32 | Menunjukkan apakah socket dapat mengirim pesan broadcast. |
| UseLoopback | 64 | Melewati perangkat keras bila memungkinkan. |
| Linger | 128 | Sistem akan memblokir proses pada percobaan tutup hingga dapat mengirim data. |
| OutOfBandInline | 256 | Menerima data out-of-band dalam aliran data normal. |
| DontLinger | n/a | Menunjukkan apakah socket akan ditutup tanpa linger. |
| ExclusiveAddressUse | n/a | Socket akan menggunakan alamat yang terikat secara eksklusif. |
| SendBuffer | 4097 | Menentukan ukuran buffer kirim. |
| ReceiveBuffer | 4098 | Menentukan ukuran buffer terima. |
| SendLowWater | 4099 | Menentukan jumlah minimum data untuk operasi kirim. |
| ReceiveLowWater | 4100 | Menentukan jumlah minimum data untuk operasi terima. |
| SendTimeout | 4101 | Menentukan batas waktu untuk operasi kirim sinkron. |
| ReceiveTimeout | 4102 | Menentukan batas waktu untuk operasi terima sinkron. |
| Error | 4103 | Mengembalikan status kesalahan dan membersihkan. |
| Type | 4104 | Mengembalikan tipe socket. |
| ReuseUnicastPort | 12295 | Menunjukkan apakah sistem harus menunda alokasi port ephemeris untuk koneksi keluar. |
| MaxConnections | 2147483647 | Opsi ini tidak didukung. Ini digunakan untuk menentukan panjang antre maksimum untuk mendengarkan. |
| IPOptions | 1 | Menentukan opsi IP yang harus disisipkan ke datagram keluar. |
| HeaderIncluded | 2 | Header disertakan ke datagram keluar. |
| TypeOfService | 3 | Mengubah tipe header IP pada bidang layanan. |
| IpTimeToLive | 4 | Waktu hidup IP. |
| MulticastInterface | 9 | Atur antarmuka untuk paket multicast keluar. |
| MulticastTimeToLive | 10 | Waktu hidup multicast IP. |
| MulticastLoopback | 11 | Loopback Multicast IP. |
| AddMembership | 12 | Menambahkan keanggotaan grup IP. |
| DropMembership | 13 | Menghapus keanggotaan grup IP. |
| DontFragment | 14 | Jangan fragmentasikan datagram IP. |
| AddSourceMembership | 15 | Bergabung dengan grup/sumber IP. |
| DropSourceMembership | 16 | Menghapus grup/sumber IP. |
| BlockSource | 17 | Memblokir grup/sumber IP. |
| UnblockSource | 18 | Membuka blokir grup/sumber IP. |
| PacketInformation | 19 | Menerima informasi paket untuk IPv4. |
| HopLimit | 21 | Mengirimkan integer yang berisi jumlah HOP paket. |
| IPProtectionLevel | 23 | Mengaktifkan pembatasan socket IPv6 ke ruang lingkup yang ditentukan. |
| IPv6Only | 27 | Socket hanya dibatasi untuk mengirim dan menerima paket IPv6. |
| NoDelay | 1 | Menonaktifkan algoritma Nagle untuk menggabungkan paket kirim. |
| BsdUrgent | 2 | Gunakan data mendesak seperti yang didefinisikan dalam RFC-1222. |
| Expedited | 2 | Gunakan data dipercepat seperti yang didefinisikan dalam RFC-1222. |
| NoChecksum | 1 | Kirim datagram UDP dengan checksum diatur ke nol. |
| ChecksumCoverage | 20 | Atur atau dapatkan cakupan checksum UDP. |
| UpdateAcceptContext | 28683 | Memperbarui socket klien dengan properti yang sama seperti socket yang mendengarkan. |
| UpdateConnectContext | 28688 | Memperbarui socket klien dengan properti yang sama seperti socket yang mendengarkan. |

## Lihat Juga

* Ruang Nama [System::Net::Sockets](../)
* Pustaka [Aspose.Slides](../../)