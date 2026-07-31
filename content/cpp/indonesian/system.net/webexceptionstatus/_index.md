---
title: WebExceptionStatus
second_title: Referensi API Aspose.Slides untuk C++
description: Menumerasi kode status kelas WebException.
type: docs
weight: 651
url: /id/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Menumerasikan kode status dari kelas WebException.

```cpp
enum class WebExceptionStatus
```

### Values

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Success | 0 | Tidak ada kesalahan yang terjadi. |
| NameResolutionFailure | 1 | Layanan pemecah nama tidak dapat menyelesaikan nama host. |
| ConnectFailure | 2 | Poin layanan remote tidak dapat dihubungi pada tingkat transport. |
| ReceiveFailure | 3 | Respons lengkap tidak diterima dari server remote. |
| SendFailure | 4 | Permintaan lengkap tidak dapat dikirim ke server remote. |
| PipelineFailure | 5 | Permintaan tersebut merupakan permintaan berpipeline dan koneksi ditutup sebelum respons diterima. |
| RequestCanceled | 6 | Permintaan dibatalkan atau terjadi kesalahan yang tidak dapat diklasifikasikan. |
| ProtocolError | 7 | Respons yang diterima dari server lengkap tetapi menunjukkan kesalahan pada level protokol. |
| ConnectionClosed | 8 | Koneksi ditutup secara prematur. |
| TrustFailure | 9 | Sertifikat server tidak dapat divalidasi. |
| SecureChannelFailure | 10 | Terjadi kesalahan saat membangun koneksi menggunakan SSL. |
| ServerProtocolViolation | 11 | Respons server bukan merupakan respons HTTP yang valid. |
| KeepAliveFailure | 12 | Koneksi untuk permintaan yang menyertakan header 'Keep-Alive' ditutup secara tidak terduga. |
| Pending | 13 | Permintaan asinkron internal masih tertunda. |
| Timeout | 14 | Tidak ada respons yang diterima selama periode tunggu untuk sebuah permintaan. |
| ProxyNameResolutionFailure | 15 | Layanan pemecah nama tidak dapat menyelesaikan nama host proksi. |
| UnknownError | 16 | Terjadi pengecualian dengan tipe yang tidak diketahui. |
| MessageLengthLimitExceeded | 17 | Pesan yang melebihi batas yang ditentukan telah diterima. |
| CacheEntryNotFound | 18 | Entri cache yang ditentukan tidak ditemukan. |
| RequestProhibitedByCachePolicy | 19 | Permintaan tidak diizinkan oleh kebijakan cache. |
| RequestProhibitedByProxy | 20 | Permintaan ini tidak diizinkan oleh proksi. |

## Lihat Juga

* Ruang Nama [System::Net](../)
* Perpustakaan [Aspose.Slides](../../)