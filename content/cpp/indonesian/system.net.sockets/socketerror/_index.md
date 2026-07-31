---
title: SocketError
second_title: Referensi API Aspose.Slides untuk C++
description: Mendaftarkan tipe kesalahan socket.
type: docs
weight: 209
url: /id/system.net.sockets/socketerror/
---
## SocketError enum

Mendaftarkan tipe kesalahan socket.

```cpp
enum class SocketError
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Success | 0 | Operasi socket selesai dengan sukses. |
| SocketError | -1 | Terjadi kesalahan socket yang tidak ditentukan. |
| Interrupted | 10004 | Panggilan socket yang memblokir dibatalkan. |
| AccessDenied | 10013 | Akses ke socket ditolak. |
| Fault | 10014 | Alamat pointer tidak valid terdeteksi. |
| InvalidArgument | 10022 | Argumen tidak valid diberikan. |
| TooManyOpenSockets | 10024 | Terlalu banyak socket terbuka pada penyedia socket yang mendasarinya. |
| WouldBlock | 10035 | Operasi tidak dapat diselesaikan secara langsung pada socket non-blokir. |
| InProgress | 10036 | Operasi memblokir sedang berlangsung. |
| AlreadyInProgress | 10037 | Socket non-blokir sudah memiliki operasi yang berjalan. |
| NotSocket | 10038 | Upaya memanggil operasi socket pada non-socket. |
| DestinationAddressRequired | 10039 | Alamat yang diperlukan tidak disertakan dalam operasi socket. |
| MessageSize | 10040 | Datagram terlalu panjang. |
| ProtocolType | 10041 | Tipe protokol tidak didukung oleh socket ini. |
| ProtocolOption | 10042 | Opsi atau level yang tidak dikenal, tidak valid, atau tidak didukung digunakan. |
| ProtocolNotSupported | 10043 | Protokol tidak diimplementasikan atau tidak dikonfigurasi. |
| SocketNotSupported | 10044 | Keluarga alamat tidak mendukung socket yang ditentukan. |
| OperationNotSupported | 10045 | Keluarga protokol tidak mendukung keluarga alamat. |
| ProtocolFamilyNotSupported | 10046 | Keluarga protokol tidak diimplementasikan atau tidak dikonfigurasi. |
| AddressFamilyNotSupported | 10047 | Keluarga alamat yang ditentukan tidak didukung. |
| AddressAlreadyInUse | 10048 | Alamat hanya dapat digunakan satu kali. |
| AddressNotAvailable | 10049 | Alamat IP yang dipilih tidak valid dalam konteks ini. |
| NetworkDown | 10050 | Jaringan tidak tersedia. |
| NetworkUnreachable | 10051 | Tidak ada rute ke host remote. |
| NetworkReset | 10052 | Aplikasi mencoba mengatur 'Keep-Alive' pada koneksi yang sudah kedaluwarsa. |
| ConnectionAborted | 10053 | Koneksi dibatalkan. |
| ConnectionReset | 10054 | Koneksi direset oleh peer remote. |
| NoBufferSpaceAvailable | 10055 | Tidak ada ruang buffer bebas yang tersedia untuk operasi socket. |
| IsConnected | 10056 | Socket sudah terhubung. |
| NotConnected | 10057 | Aplikasi mencoba mengirim atau menerima data, tetapi socket tidak terhubung. |
| Shutdown | 10058 | Permintaan untuk mengirim atau menerima data dilarang karena socket sudah ditutup. |
| TimedOut | 10060 | Percobaan koneksi habis waktu, atau host yang terhubung gagal merespons. |
| ConnectionRefused | 10061 | Host remote secara aktif menolak koneksi. |
| HostDown | 10064 | Operasi gagal karena host remote tidak aktif. |
| HostUnreachable | 10065 | Tidak ada rute jaringan ke host yang ditentukan. |
| ProcessLimit | 10067 | Terjadi terlalu banyak proses yang menggunakan penyedia socket yang mendasarinya. |
| SystemNotReady | 10091 | Subsystem jaringan tidak tersedia. |
| VersionNotSupported | 10092 | Versi penyedia socket yang mendasari berada di luar jangkauan. |
| NotInitialized | 10093 | Penyedia socket yang mendasari tidak diinisialisasi. |
| Disconnecting | 10101 | Penutupan yang bersahabat sedang berlangsung. |
| TypeNotFound | 10109 | Kelas yang ditentukan tidak ditemukan. |
| HostNotFound | 11001 | Host yang ditentukan tidak dikenal. |
| TryAgain | 11002 | Nama host tidak dapat diselesaikan. |
| NoRecovery | 11003 | Kesalahan tidak dapat dipulihkan atau basis data yang diminta tidak dapat ditemukan. |
| NoData | 11004 | Nama atau alamat IP yang diminta tidak ditemukan pada server nama. |

## Lihat Juga

* Namespace [System::Net::Sockets](../)
* Perpustakaan [Aspose.Slides](../../)