---
title: IVideo class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ivideo/
---
## IVideo kelas

Merepresentasikan video yang disematkan ke dalam presentasi.

Tipe IVideo membuka anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`content_type`](/slides/python-net/id/aspose.slides/ivideo/content_type/) | Mengembalikan tipe MIME dari sebuah video, dienkode dalam [`IVideo.binary_data`](/slides/python-net/id/aspose.slides/ivideo/binary_data).<br/>            Baca-saja **str**. |
| [`binary_data`](/slides/python-net/id/aspose.slides/ivideo/binary_data/) | Mengembalikan salinan data audio. Jika jumlah data besar, pertimbangkan penggunaan <br/>            metode [`IVideo.get_stream`](/slides/python-net/id/aspose.slides/ivideo/get_stream) untuk mencegah pemuatan data video yang tidak perlu ke memori <br/>            atau bahkan OutOfMemoryException.<br/>            Baca-saja **int**[]. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/id/aspose.slides/ivideo/get_stream/#) | Mengembalikan aliran Stream untuk membaca.<br/>            Gunakan 'using' atau tutup aliran setelah selesai digunakan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)