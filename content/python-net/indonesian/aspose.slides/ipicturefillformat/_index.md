---
title: IPictureFillFormat class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat kelas

Mewakili gaya isi gambar.

Tipe IPPictureFillFormat mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`dpi`](/slides/python-net/id/aspose.slides/ipicturefillformat/dpi/) | Mengembalikan atau mengatur dpi yang digunakan untuk mengisi gambar.<br/>            Baca/tulis **int**. |
| [`picture_fill_mode`](/slides/python-net/id/aspose.slides/ipicturefillformat/picture_fill_mode/) | Mengembalikan atau mengatur mode isi gambar.<br/>            Baca/tulis [`PictureFillMode`](/slides/python-net/id/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/id/aspose.slides/ipicturefillformat/picture/) | Mengembalikan gambar.<br/>            Hanya baca [`ISlidesPicture`](/slides/python-net/id/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/id/aspose.slides/ipicturefillformat/crop_left/) | Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong<br/>            di sebelah kiri gambar. <br/>            Baca/tulis **float**. |
| [`crop_top`](/slides/python-net/id/aspose.slides/ipicturefillformat/crop_top/) | Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong<br/>            di bagian atas gambar. <br/>            Baca/tulis **float**. |
| [`crop_right`](/slides/python-net/id/aspose.slides/ipicturefillformat/crop_right/) | Mengembalikan atau mengatur persentase lebar gambar asli yang dipotong<br/>            di sebelah kanan gambar. <br/>            Baca/tulis **float**. |
| [`crop_bottom`](/slides/python-net/id/aspose.slides/ipicturefillformat/crop_bottom/) | Mengembalikan atau mengatur persentase tinggi gambar asli yang dipotong<br/>            di bagian bawah gambar. <br/>            Baca/tulis **float**. |
| [`stretch_offset_left`](/slides/python-net/id/aspose.slides/ipicturefillformat/stretch_offset_left/) | Mengembalikan atau mengatur tepi kiri persegi isi yang didefinisikan oleh offset persentase <br/>            dari tepi kiri kotak pembatas bentuk. <br/>            Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset.<br/>            Baca/tulis **float**. |
| [`stretch_offset_top`](/slides/python-net/id/aspose.slides/ipicturefillformat/stretch_offset_top/) | Mengembalikan atau mengatur tepi atas persegi isi yang didefinisikan oleh offset persentase <br/>            dari tepi atas kotak pembatas bentuk.<br/>            Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset.<br/>            Baca/tulis **float**. |
| [`stretch_offset_right`](/slides/python-net/id/aspose.slides/ipicturefillformat/stretch_offset_right/) | Mengembalikan atau mengatur tepi kanan persegi isi yang didefinisikan oleh offset persentase <br/>            dari tepi kanan kotak pembatas bentuk.<br/>            Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset.<br/>            Baca/tulis **float**. |
| [`stretch_offset_bottom`](/slides/python-net/id/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Mengembalikan atau mengatur tepi bawah persegi isi yang didefinisikan oleh offset persentase <br/>            dari tepi bawah kotak pembatas bentuk.<br/>            Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset.<br/>            Baca/tulis **float**. |
| [`tile_offset_x`](/slides/python-net/id/aspose.slides/ipicturefillformat/tile_offset_x/) | Mengembalikan atau mengatur offset horizontal tekstur dari asal bentuk dalam poin.<br/>             Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri.<br/>             Baca/tulis **float**. |
| [`tile_offset_y`](/slides/python-net/id/aspose.slides/ipicturefillformat/tile_offset_y/) | Mengembalikan atau mengatur offset vertikal tekstur dari asal bentuk dalam poin.<br/>             Nilai positif memindahkan tekstur ke bawah, sementara nilai negatif memindahkannya ke atas.<br/>             Baca/tulis **float**. |
| [`tile_scale_x`](/slides/python-net/id/aspose.slides/ipicturefillformat/tile_scale_x/) | Mengembalikan atau mengatur skala horizontal untuk isi tekstur sebagai persentase.<br/>             Baca/tulis **float**. |
| [`tile_scale_y`](/slides/python-net/id/aspose.slides/ipicturefillformat/tile_scale_y/) | Mengembalikan atau mengatur skala vertikal untuk isi tekstur sebagai persentase.<br/>             Baca/tulis **float**. |
| [`tile_alignment`](/slides/python-net/id/aspose.slides/ipicturefillformat/tile_alignment/) | Mengembalikan atau mengatur cara tekstur disejajarkan di dalam bentuk. Pengaturan ini mengontrol titik mulai pola tekstur dan cara pengulangannya di seluruh bentuk.<br/>             Baca/tulis [`RectangleAlignment`](/slides/python-net/id/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/id/aspose.slides/ipicturefillformat/tile_flip/) | Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya.<br/>             Baca/tulis [`TileFlip`](/slides/python-net/id/aspose.slides/tileflip). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/id/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran shape dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/id/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Mengompres gambar dengan mengurangi ukurannya berdasarkan ukuran shape dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/id/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Menghapus area yang dipotong dari Picture isi. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)