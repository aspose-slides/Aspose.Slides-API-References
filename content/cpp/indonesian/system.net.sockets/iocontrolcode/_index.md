---
title: IOControlCode
second_title: Referensi API Aspose.Slides untuk C++
description: Mendaftar kode kontrol IO.
type: docs
weight: 157
url: /id/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Mendaftar kode kontrol [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| AsyncIO | -2147195267 | Mengaktifkan atau menonaktifkan mode I/O asynchronous pada socket. |
| NonBlockingIO | -2147195266 | Menandai socket sebagai nonblocking. |
| DataToRead | 1074030207 | Mengembalikan jumlah byte yang tersedia untuk dibaca. |
| OobDataRead | 1074033415 | Mengembalikan informasi tentang data out-of-band yang menunggu untuk diterima. |
| AssociateHandle | -2013265919 | Mengaitkan socket ini dengan handle yang ditentukan dari antarmuka pasangan. |
| EnableCircularQueuing | 671088642 | Mengganti datagram terlama dalam antrian dengan yang masuk ketika antrian pesan masuk penuh. |
| Flush | 671088644 | Membuang isi saat ini dari antrian pengiriman yang terkait dengan socket ini. |
| GetBroadcastAddress | 1207959557 | Mengembalikan struktur SOCKADDR yang berisi alamat broadcast untuk keluarga alamat socket saat ini. |
| GetExtensionFunctionPointer | -939524090 | Mendapatkan pointer ke fungsi ekstensi yang ditentukan yang didukung oleh penyedia layanan terkait. |
| GetQos | -939524089 | Mengambil struktur QOS yang terkait dengan socket. |
| GetGroupQos | -939524088 | Mengembalikan atribut QOS untuk grup socket. |
| MultipointLoopback | -2013265911 | Mengontrol apakah data yang dikirim oleh aplikasi pada komputer lokal (tidak harus oleh socket yang sama) dalam sesi multicast akan diterima oleh socket yang bergabung dengan grup tujuan multicast pada antarmuka loopback. |
| MulticastScope | -2013265910 | Mengontrol jumlah kali paket multicast dapat diteruskan oleh router, yang juga dikenal sebagai TTL atau hop count. |
| SetQos | -2013265909 | Mengatur atribut QOS untuk socket. |
| SetGroupQos | -2013265908 | Mengatur atribut QOS untuk grup socket. |
| TranslateHandle | -939524083 | Mengembalikan handle untuk socket yang berlaku dalam konteks antarmuka pasangan. |
| RoutingInterfaceQuery | -939524076 | Mengembalikan alamat antarmuka yang dapat digunakan untuk terhubung ke alamat remote yang ditentukan. |
| RoutingInterfaceChange | -2013265899 | Mengaktifkan penerimaan notifikasi ketika antarmuka lokal yang digunakan untuk mengakses titik akhir remote berubah. |
| AddressListQuery | 1207959574 | Mengembalikan daftar antarmuka lokal yang dapat di-bind oleh socket. |
| AddressListChange | 671088663 | Mengaktifkan penerimaan notifikasi ketika daftar antarmuka lokal untuk keluarga protokol socket berubah. |
| QueryTargetPnpHandle | 1207959576 | Mendapatkan handle SOCKET penyedia yang mendasari. |
| NamespaceChange | -2013265895 | Mengontrol apakah socket menerima notifikasi ketika kueri namespace menjadi tidak valid. |
| AddressListSort | -939524071 | Mengurutkan daftar alamat tujuan IPv6 dan IPv4 untuk menentukan alamat terbaik yang tersedia untuk membuat koneksi. |
| ReceiveAll | -1744830463 | Mengaktifkan penerimaan semua paket IPv4 pada jaringan. |
| ReceiveAllMulticast | -1744830462 | Mengaktifkan penerimaan semua paket multicast IPv4 pada jaringan. |
| ReceiveAllIgmpMulticast | -1744830461 | Mengaktifkan penerimaan semua paket IGMP pada jaringan. |
| KeepAliveValues | -1744830460 | Mengontrol pengiriman paket TCP keep-alive dan interval pengirimannya. |
| AbsorbRouterAlert | -1744830459 | Nilai ini sama dengan konstanta Winsock 2 'SIO_ABSORB_RTRALERT'. |
| UnicastInterface | -1744830458 | Mengatur antarmuka yang digunakan untuk paket unicast keluar. |
| LimitBroadcasts | -1744830457 | Nilai ini sama dengan konstanta Winsock 2 'SIO_LIMIT_BROADCASTS'. |
| BindToInterface | -1744830456 | Membind socket ke indeks antarmuka yang ditentukan. |
| MulticastInterface | -1744830455 | Mengatur antarmuka yang digunakan untuk paket multicast keluar. |
| AddMulticastGroupOnInterface | -1744830454 | Bergabung dengan grup multicast menggunakan antarmuka yang diidentifikasi dengan indeksnya. |
| DeleteMulticastGroupFromInterface | -1744830453 | Menghapus socket dari grup multicast. |

## Lihat Juga

* Ruang Nama [System::Net::Sockets](../)
* Pustaka [Aspose.Slides](../../)