---
title: IAudio class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iaudio/
---
## IAudio kelas

Mewakili file audio yang tertanam.

Tipe IAudio menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`content_type`](/slides/python-net/id/aspose.slides/iaudio/content_type/) | Mengembalikan tipe MIME audio, yang dikodekan dalam [`IAudio.binary_data`](/slides/python-net/id/aspose.slides/iaudio/binary_data).<br/>            Hanya-baca **str**. |
| [`binary_data`](/slides/python-net/id/aspose.slides/iaudio/binary_data/) | Mengembalikan salinan data audio. Jika data berukuran besar, pertimbangkan <br/>            penggunaan metode [`IAudio.get_stream`](/slides/python-net/id/aspose.slides/iaudio/get_stream) untuk mencegah pemuatan data audio yang tidak diperlukan<br/>            ke memori atau bahkan OutOfMemoryException.<br/>            Hanya-baca **int**[]. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/id/aspose.slides/iaudio/get_stream/#) | Mengembalikan aliran Stream untuk membaca.<br/>            Gunakan 'using' atau tutup aliran setelah digunakan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)