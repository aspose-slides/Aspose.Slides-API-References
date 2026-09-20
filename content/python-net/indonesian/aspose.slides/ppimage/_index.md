---
title: PPImage class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ppimage/
---
## PPImage kelas

Mewakili sebuah gambar dalam presentasi.

Tipe PPImage menampilkan anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/id/aspose.slides/ppimage/binary_data/) | Mengembalikan salinan data gambar.<br/>            Hanya baca **int**[]. |
| [`image`](/slides/python-net/id/aspose.slides/ppimage/image/) | Mengembalikan salinan gambar.<br/>            Hanya baca [`IImage`](/slides/python-net/id/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/id/aspose.slides/ppimage/svg_image/) | Mengembalikan atau mengatur objek ISvgImage [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/id/aspose.slides/ppimage/content_type/) | Mengembalikan tipe MIME dari gambar, dienkode dalam [`PPImage.binary_data`](/slides/python-net/id/aspose.slides/ppimage/binary_data).<br/>            Hanya baca **str**. |
| [`width`](/slides/python-net/id/aspose.slides/ppimage/width/) | Mengembalikan lebar gambar.<br/>            Hanya baca **int**. |
| [`height`](/slides/python-net/id/aspose.slides/ppimage/height/) | Mengembalikan tinggi gambar.<br/>            Hanya baca **int**. |
| [`x`](/slides/python-net/id/aspose.slides/ppimage/x/) | Mengembalikan offset X gambar.<br/>            Hanya baca **int**. |
| [`y`](/slides/python-net/id/aspose.slides/ppimage/y/) | Mengembalikan offset Y gambar.<br/>            Hanya baca **int**. |

## Metode

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/id/aspose.slides/ppimage/replace_image/#bytes) | Mengganti data gambar.<br/>            Data gambar baru. Ketika parameter newImageData adalah None. |
| [`replace_image(self, new_image)`](/slides/python-net/id/aspose.slides/ppimage/replace_image/#iimage) | Mengganti data gambar. Perhatian: ketika Image adalah metafile - akan dirasterkan. Gunakan ReplaceImage(byte[]) sebagai gantinya<br/>            Gambar baru. Ketika parameter newImage adalah None. |
| [`replace_image(self, new_image)`](/slides/python-net/id/aspose.slides/ppimage/replace_image/#ippimage) | Mengganti data gambar.<br/>            IPPImage baru. Ketika parameter newImage adalah None. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)