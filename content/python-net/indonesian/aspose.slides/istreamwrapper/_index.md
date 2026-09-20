---
title: IStreamWrapper class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/istreamwrapper/
---
## IStreamWrapper kelas

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## Properti

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/id/aspose.slides/istreamwrapper/stream/) | Mendapatkan sebuah stream.<br/>            Hanya-baca **io.RawIOBase**. |
| [`can_read`](/slides/python-net/id/aspose.slides/istreamwrapper/can_read/) | Mendapatkan nilai yang menunjukkan apakah stream saat ini mendukung pembacaan.<br/>            Hanya-baca **bool**. |
| [`can_seek`](/slides/python-net/id/aspose.slides/istreamwrapper/can_seek/) | Mendapatkan nilai yang menunjukkan apakah stream saat ini mendukung pencarian.<br/>            Hanya-baca **bool**. |
| [`can_write`](/slides/python-net/id/aspose.slides/istreamwrapper/can_write/) | Mendapatkan nilai yang menunjukkan apakah stream saat ini mendukung penulisan.<br/>            Hanya-baca **bool**. |
| [`length`](/slides/python-net/id/aspose.slides/istreamwrapper/length/) | Mendapatkan panjang dalam byte dari stream.<br/>            Hanya-baca **int**. |
| [`position`](/slides/python-net/id/aspose.slides/istreamwrapper/position/) | Mendapatkan posisi dalam stream saat ini.<br/>            Hanya-baca **int**. |

## Metode

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/id/aspose.slides/istreamwrapper/close/#) | Menutup stream saat ini dan melepaskan semua sumber daya. |
| [`flush(self)`](/slides/python-net/id/aspose.slides/istreamwrapper/flush/#) | Mengosongkan semua buffer untuk stream ini dan menyebabkan data yang di-buffer ditulis ke perangkat dasar. |
| [`read(self, buffer, offset, count)`](/slides/python-net/id/aspose.slides/istreamwrapper/read/#bytes-int-int) | Membaca urutan byte dari stream saat ini dan menggeser posisi dalam stream sebanyak jumlah byte yang dibaca. |
| [`read_byte(self)`](/slides/python-net/id/aspose.slides/istreamwrapper/read_byte/#) | Membaca satu byte dari stream dan menggeser posisi dalam stream satu byte, atau mengembalikan -1 jika berada di akhir stream. |
| [`seek(self, offset, origin)`](/slides/python-net/id/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Mengatur posisi dalam stream saat ini |
| [`write(self, buffer, offset, count)`](/slides/python-net/id/aspose.slides/istreamwrapper/write/#bytes-int-int) | Menulis urutan byte ke stream saat ini dan menggeser posisi saat ini dalam stream ini sebanyak jumlah byte yang ditulis. |
| [`write_byte(self, value)`](/slides/python-net/id/aspose.slides/istreamwrapper/write_byte/#int) | Menulis satu byte ke posisi saat ini dalam stream dan menggeser posisi dalam stream satu byte. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)