---
title: HtmlOptions class
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.export/htmloptions/
---
## HtmlOptions kelas

Mewakili opsi pengeksporan HTML.

**Pewarisan:**[`HtmlOptions`](/slides/python-net/id/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)

Tipe HtmlOptions memperlihatkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/id/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Membuat objek HtmlOptions baru yang menentukan callback. |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/htmloptions/__init__/#) | Membuat objek HtmlOptions baru untuk menyimpan ke dalam satu berkas HTML. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/htmloptions/warning_callback/) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/htmloptions/progress_callback/) | Mewakili objek callback untuk memperbarui progres penyimpanan dalam persentase.<br/>            Lihat [`IProgressCallback`](/slides/python-net/id/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/htmloptions/default_regular_font/) | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/htmloptions/gradient_style/) | Mengembalikan atau mengatur gaya visual gradien.<br/>            Baca/tulis [`GradientStyle`](/slides/python-net/id/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/htmloptions/skip_java_script_links/) | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi.<br/>            Baca/tulis **bool**. Nilai defaultnya adalah **false**. |
| [`slides_layout_options`](/slides/python-net/id/aspose.slides.export/htmloptions/slides_layout_options/) | Mengambil atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](/slides/python-net/id/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/htmloptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Baca-saja [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/htmloptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Defaultnya adalah `false`. |
| [`html_formatter`](/slides/python-net/id/aspose.slides.export/htmloptions/html_formatter/) | Mengembalikan atau mengatur templat HTML.<br/>            Baca/tulis [`IHtmlFormatter`](/slides/python-net/id/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/id/aspose.slides.export/htmloptions/disable_font_ligatures/) | Mengambil atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur.<br/>            Ketika diatur ke `true`, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke `false`. |
| [`slide_image_format`](/slides/python-net/id/aspose.slides.export/htmloptions/slide_image_format/) | Mengembalikan atau mengatur opsi format gambar slide.<br/>            Baca/tulis [`ISlideImageFormat`](/slides/python-net/id/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/id/aspose.slides.export/htmloptions/jpeg_quality/) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF.<br/>            Baca/tulis **int**. |
| [`pictures_compression`](/slides/python-net/id/aspose.slides.export/htmloptions/pictures_compression/) | Mewakili tingkat kompresi gambar |
| [`delete_pictures_cropped_areas`](/slides/python-net/id/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Bendera boolean yang menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true, bagian yang dipotong akan dihapus, jika false mereka akan diserialisasi dalam dokumen (yang dapat menyebabkan berkas menjadi lebih besar) |
| [`svg_responsive_layout`](/slides/python-net/id/aspose.slides.export/htmloptions/svg_responsive_layout/) | True untuk mengecualikan atribut lebar dan tinggi dari kontainer svg - ini akan membuat tata letak responsif. False - sebaliknya.<br/>            Baca/tulis **bool**. |

### Lihat Juga
* kelas [`HtmlOptions`](/slides/python-net/id/aspose.slides.export/htmloptions)
* kelas [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)