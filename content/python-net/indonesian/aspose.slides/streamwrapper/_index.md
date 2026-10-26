---
title: StreamWrapper class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/streamwrapper/
---
## StreamWrapper kelas

Pembungkus Aspose.IO.Stream untuk antarmuka COM.

Tipe StreamWrapper mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`stream`](/slides/python-net/id/aspose.slides/streamwrapper/stream/) | Mendapatkan sebuah aliran.<br/>            Hanya baca **io.RawIOBase**. |
| [`can_read`](/slides/python-net/id/aspose.slides/streamwrapper/can_read/) | Mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pembacaan.<br/>            Hanya baca **bool**. |
| [`can_seek`](/slides/python-net/id/aspose.slides/streamwrapper/can_seek/) | Mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung penelusuran.<br/>            Hanya baca **bool**. |
| [`can_write`](/slides/python-net/id/aspose.slides/streamwrapper/can_write/) | Mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung penulisan.<br/>            Hanya baca **bool**. |
| [`length`](/slides/python-net/id/aspose.slides/streamwrapper/length/) | Mendapatkan panjang dalam byte dari aliran.<br/>            Hanya baca **int**. |
| [`position`](/slides/python-net/id/aspose.slides/streamwrapper/position/) | Mendapatkan atau mengatur posisi dalam aliran saat ini.<br/>            Hanya baca **int**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`close(self)`](/slides/python-net/id/aspose.slides/streamwrapper/close/#) | Menutup aliran saat ini dan membebaskan semua sumber daya. |
| [`flush(self)`](/slides/python-net/id/aspose.slides/streamwrapper/flush/#) | Mengosongkan semua buffer untuk aliran ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| [`read(self, buffer, offset, count)`](/slides/python-net/id/aspose.slides/streamwrapper/read/#bytes-int-int) | Membaca urutan byte dari aliran saat ini dan menggeser posisi dalam aliran sebanyak jumlah byte yang dibaca. |
| [`read_byte(self)`](/slides/python-net/id/aspose.slides/streamwrapper/read_byte/#) | Membaca satu byte dari aliran dan menggeser posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| [`seek(self, offset, origin)`](/slides/python-net/id/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Mengatur posisi dalam aliran saat ini |
| [`write(self, buffer, offset, count)`](/slides/python-net/id/aspose.slides/streamwrapper/write/#bytes-int-int) | Menulis urutan byte ke aliran saat ini dan menggeser posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis. |
| [`write_byte(self, value)`](/slides/python-net/id/aspose.slides/streamwrapper/write_byte/#int) | Menulis satu byte ke posisi saat ini dalam aliran dan menggeser posisi dalam aliran satu byte. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)