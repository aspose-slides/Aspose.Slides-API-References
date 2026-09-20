---
title: SVGOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/svgoptions/
---
## kelas SVGOptions

Mewakili opsi SVG.

**Warisan:**[`SVGOptions`](/slides/python-net/id/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)

Tipe SVGOptions menampilkan anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/svgoptions/__init__/#) | Menginisialisasi instance baru dari kelas SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/id/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Menginisialisasi instance baru dari kelas SVGOptions dengan menentukan objek pengendali penyematan tautan. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/svgoptions/warning_callback/) | Mengembalikan atau menetapkan sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/svgoptions/progress_callback/) | Mewakili objek callback untuk menyimpan pembaruan kemajuan dalam persentase.<br/>            Lihat [`IProgressCallback`](/slides/python-net/id/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/svgoptions/default_regular_font/) | Mengembalikan atau menetapkan font yang digunakan jika font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/svgoptions/gradient_style/) | Mengembalikan atau menetapkan gaya visual gradien.<br/>            Baca/tulis [`GradientStyle`](/slides/python-net/id/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/svgoptions/skip_java_script_links/) | Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi.<br/>            Baca/tulis **bool**. Nilai defaultnya adalah **false**. |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/svgoptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Baca-saja [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/id/aspose.slides.export/svgoptions/use_frame_size/) | Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak.<br/>            Baca/tulis **bool**.<br/>            Nilai defaultnya adalah false. |
| [`use_frame_rotation`](/slides/python-net/id/aspose.slides.export/svgoptions/use_frame_rotation/) | Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat render atau tidak.<br/>            Baca/tulis **bool**.<br/>            Nilai defaultnya adalah true. |
| [`vectorize_text`](/slides/python-net/id/aspose.slides.export/svgoptions/vectorize_text/) | Menentukan apakah teks pada slide akan disimpan sebagai grafik.<br/>            Baca/tulis **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/id/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Mengembalikan atau menetapkan batas resolusi rendah untuk rasterisasi metafile.<br/>            Baca/tulis **int**. |
| [`disable_3d_text`](/slides/python-net/id/aspose.slides.export/svgoptions/disable_3d_text/) | Menentukan apakah teks 3D dinonaktifkan dalam SVG.<br/>            Baca/tulis **bool**. |
| [`disable_gradient_split`](/slides/python-net/id/aspose.slides.export/svgoptions/disable_gradient_split/) | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter.<br/>            Baca/tulis **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/id/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda.<br/>            Mesin penulisan SVG Aspose.Slides memiliki solusi untuk masalah tersebut:<br/>            ia memotong ujung garis dengan panah, sehingga garis tidak menindihi penanda.<br/>            Opsi ini menonaktifkan perilaku tersebut.<br/>            Baca/tulis **bool**. |
| [`default`](/slides/python-net/id/aspose.slides.export/svgoptions/default/) | Mengembalikan pengaturan default.<br/>            Baca-saja [`SVGOptions`](/slides/python-net/id/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/id/aspose.slides.export/svgoptions/simple/) | Mengembalikan pengaturan untuk generasi file SVG yang paling sederhana dan terkecil.<br/>            Baca-saja [`SVGOptions`](/slides/python-net/id/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/id/aspose.slides.export/svgoptions/wysiwyg/) | Mengembalikan pengaturan untuk generasi file SVG yang paling akurat.<br/>            Baca-saja [`SVGOptions`](/slides/python-net/id/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/id/aspose.slides.export/svgoptions/jpeg_quality/) | Menentukan kualitas enkoding JPEG.<br/>            Baca/tulis **int**. |
| [`shape_formatting_controller`](/slides/python-net/id/aspose.slides.export/svgoptions/shape_formatting_controller/) | Mengembalikan dan menetapkan antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk.<br/>            Baca/tulis [`ISvgShapeFormattingController`](/slides/python-net/id/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/id/aspose.slides.export/svgoptions/pictures_compression/) | Mewakili tingkat kompresi gambar |
| [`delete_pictures_cropped_areas`](/slides/python-net/id/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Bendera boolean yang menunjukkan apakah bagian yang dipotong tetap menjadi bagian dokumen. Jika true, bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar) |
| [`external_fonts_handling`](/slides/python-net/id/aspose.slides.export/svgoptions/external_fonts_handling/) | Menentukan cara menangani font yang dimuat secara eksternal.<br/>            Baca/tulis [`SvgExternalFontsHandling`](/slides/python-net/id/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/id/aspose.slides.export/svgoptions/disable_font_ligatures/) | Mengambil atau menetapkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur.<br/>            Ketika disetel ke `true`, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke `false`. |


### Lihat Juga
* kelas [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)
* kelas [`SVGOptions`](/slides/python-net/id/aspose.slides.export/svgoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)