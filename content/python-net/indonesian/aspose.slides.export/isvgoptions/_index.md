---
title: ISVGOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/isvgoptions/
---
## ISVGOptions kelas

Mewakili opsi SVG.

Tipe ISVGOptions mengekspos anggota-anggota berikut:

## Properties

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/id/aspose.slides.export/isvgoptions/vectorize_text/) | Menentukan apakah teks pada slide akan disimpan sebagai grafik.<br/>            Baca/tulis **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/id/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile.<br/>            Baca/tulis **int**. |
| [`disable_3d_text`](/slides/python-net/id/aspose.slides.export/isvgoptions/disable_3d_text/) | Menentukan apakah teks 3D dinonaktifkan dalam SVG.<br/>            Baca/tulis **bool**. |
| [`disable_gradient_split`](/slides/python-net/id/aspose.slides.export/isvgoptions/disable_gradient_split/) | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter.<br/>            Baca/tulis **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/id/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk marker.<br/>            Mesin penulisan SVG Aspose.Slides memiliki solusi untuk masalah tersebut:<br/>            ia memotong ujung garis dengan panah, sehingga garis tidak tumpang tindih dengan marker.<br/>            Opsi ini mematikan perilaku tersebut.<br/>            Baca/tulis **bool**. |
| [`jpeg_quality`](/slides/python-net/id/aspose.slides.export/isvgoptions/jpeg_quality/) | Menentukan kualitas enkoding JPEG.<br/>            Baca/tulis **int**. |
| [`shape_formatting_controller`](/slides/python-net/id/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Mengembalikan dan mengatur antarmuka callback yang memungkinkan pengguna mengontrol konversi shape.<br/>            Baca/tulis [`ISvgShapeFormattingController`](/slides/python-net/id/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/id/aspose.slides.export/isvgoptions/pictures_compression/) | Mewakili tingkat kompresi gambar<br/>            Baca/tulis [`ISVGOptions.pictures_compression`](/slides/python-net/id/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/id/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Bendera boolean yang menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialisasi dalam dokumen (yang dapat menyebabkan file menjadi lebih besar)<br/>            Baca/tulis **bool**. |
| [`use_frame_size`](/slides/python-net/id/aspose.slides.export/isvgoptions/use_frame_size/) | Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak.<br/>            Baca/tulis **bool**.<br/>            Nilai default adalah false. |
| [`use_frame_rotation`](/slides/python-net/id/aspose.slides.export/isvgoptions/use_frame_rotation/) | Menentukan apakah melakukan rotasi yang ditentukan pada shape saat merender atau tidak.<br/>            Baca/tulis **bool**.<br/>            Nilai default adalah true. |
| [`external_fonts_handling`](/slides/python-net/id/aspose.slides.export/isvgoptions/external_fonts_handling/) | Menentukan cara menangani font yang dimuat secara eksternal.<br/>            Baca/tulis [`SvgExternalFontsHandling`](/slides/python-net/id/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/isvgoptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Hanya-baca [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/id/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur.<br/>            Ketika diset ke `true`, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diset ke `false`. |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* pustaka [`Aspose.Slides`](/slides/python-net)