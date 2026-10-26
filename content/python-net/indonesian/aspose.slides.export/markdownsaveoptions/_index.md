---
title: MarkdownSaveOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions kelas

Mewakili opsi yang mengontrol bagaimana presentasi harus disimpan ke markdown.

**Pewarisan:**[`MarkdownSaveOptions`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)

Tipe MarkdownSaveOptions mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/__init__/#) | Konstruktor. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/warning_callback/) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/progress_callback/) | Mewakili objek callback untuk memperbarui kemajuan penyimpanan dalam persentase.<br/>            Lihat [`IProgressCallback`](/slides/python-net/id/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Mengembalikan atau mengatur font yang digunakan jika font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/gradient_style/) | Mengembalikan atau mengatur gaya visual gradien.<br/>            Baca/tulis [`GradientStyle`](/slides/python-net/id/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi.<br/>            Baca/tulis **bool**. Nilai default adalah **false**. |
| [`export_type`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/export_type/) | Menentukan spesifikasi markdown untuk mengonversi presentasi.<br/>            Nilai default adalah `TextOnly`. |
| [`base_path`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/base_path/) | Menentukan jalur dasar tempat dokumen dengan sumber daya akan disimpan.<br/>            Nilai default adalah direktori saat ini dari aplikasi. |
| [`images_save_folder_name`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Menentukan nama folder untuk menyimpan gambar.<br/>            Nilai default adalah `Images`. |
| [`new_line_type`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/new_line_type/) | Menentukan apakah dokumen yang dihasilkan harus memiliki baris baru \\r(Macintosh) \\n(Unix) atau \\r\\n(Windows).<br/>            Nilai default adalah `Unix`. |
| [`show_comments`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/show_comments/) | Menentukan apakah dokumen yang dihasilkan harus menampilkan komentar atau tidak.<br/>            Nilai default adalah `false`. |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Nilai default adalah `false`. |
| [`show_slide_number`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Menentukan apakah dokumen yang dihasilkan harus menampilkan nomor setiap slide atau tidak.<br/>            Nilai default adalah `false`. |
| [`flavor`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/flavor/) | Menentukan spesifikasi markdown untuk mengonversi presentasi.<br/>            Nilai default adalah `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Mendapatkan atau mengatur string format yang digunakan untuk header nomor slide dalam output Markdown.<br/>            Format harus menyertakan placeholder \"{0}\", yang akan diganti dengan indeks slide selama ekspor.<br/>            Contoh: \"# Slide {0}\" akan menghasilkan \"# Slide 1\", \"# Slide 2\", dll. |
| [`handle_repeated_spaces`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Jika diatur ke `true`, menghapus baris kosong atau hanya spasi dari output Markdown akhir.<br/>            Nilai default adalah `false`. |

### Lihat Juga
* kelas [`MarkdownSaveOptions`](/slides/python-net/id/aspose.slides.export/markdownsaveoptions)
* kelas [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)