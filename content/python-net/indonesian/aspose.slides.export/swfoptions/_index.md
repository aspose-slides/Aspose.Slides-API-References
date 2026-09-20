---
title: SwfOptions class
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.export/swfoptions/
---
## SwfOptions kelas

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Swf.

**Pewarisan:**[`SwfOptions`](/slides/python-net/id/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)

Tipe SwfOptions menampilkan anggota-anggota berikut:

## Konstruktor

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/swfoptions/__init__/#) | Konstruktor default. |

## Properti

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/swfoptions/warning_callback/) | Mengembalikan atau mengatur objek yang menerima peringatan dan menentukan apakah proses pemuatan akan dilanjutkan atau dibatalkan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/swfoptions/progress_callback/) | Mewakili objek callback untuk pembaruan kemajuan penyimpanan dalam persentase.<br/>            Lihat [`IProgressCallback`](/slides/python-net/id/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/swfoptions/default_regular_font/) | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/swfoptions/gradient_style/) | Mengembalikan atau mengatur gaya visual dari gradasi.<br/>            Baca/tulis [`GradientStyle`](/slides/python-net/id/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/swfoptions/skip_java_script_links/) | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi.<br/>            Baca/tulis **bool**. Nilai default adalah **false**. |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/swfoptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Default adalah `false`. |
| [`compressed`](/slides/python-net/id/aspose.slides.export/swfoptions/compressed/) | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak.<br/>            Default adalah `true`. |
| [`viewer_included`](/slides/python-net/id/aspose.slides.export/swfoptions/viewer_included/) | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak.<br/>            Default adalah `true`. |
| [`show_page_border`](/slides/python-net/id/aspose.slides.export/swfoptions/show_page_border/) | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| [`show_full_screen`](/slides/python-net/id/aspose.slides.export/swfoptions/show_full_screen/) | Tampilkan/sembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true. |
| [`show_page_stepper`](/slides/python-net/id/aspose.slides.export/swfoptions/show_page_stepper/) | Tampilkan/sembunyikan pengatur langkah halaman. Dapat ditimpa dalam flashvars. Default adalah true. |
| [`show_search`](/slides/python-net/id/aspose.slides.export/swfoptions/show_search/) | Tampilkan/sembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true. |
| [`show_top_pane`](/slides/python-net/id/aspose.slides.export/swfoptions/show_top_pane/) | Tampilkan/sembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true. |
| [`show_bottom_pane`](/slides/python-net/id/aspose.slides.export/swfoptions/show_bottom_pane/) | Tampilkan/sembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true. |
| [`show_left_pane`](/slides/python-net/id/aspose.slides.export/swfoptions/show_left_pane/) | Tampilkan/sembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true. |
| [`start_open_left_pane`](/slides/python-net/id/aspose.slides.export/swfoptions/start_open_left_pane/) | Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false. |
| [`enable_context_menu`](/slides/python-net/id/aspose.slides.export/swfoptions/enable_context_menu/) | Aktifkan/nonaktifkan menu konteks. Default adalah true. |
| [`logo_image_bytes`](/slides/python-net/id/aspose.slides.export/swfoptions/logo_image_bytes/) | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas penampil.<br/>            Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan secara tidak tepat. |
| [`logo_link`](/slides/python-net/id/aspose.slides.export/swfoptions/logo_link/) | Mengambil atau mengatur alamat hyperlink penuh untuk logo.<br/>            Berpengaruh hanya jika [`SwfOptions.logo_image_bytes`](/slides/python-net/id/aspose.slides.export/swfoptions/logo_image_bytes) ditentukan. |
| [`jpeg_quality`](/slides/python-net/id/aspose.slides.export/swfoptions/jpeg_quality/) | Menentukan kualitas gambar JPEG.<br/>            Default adalah 95. |
| [`slides_layout_options`](/slides/python-net/id/aspose.slides.export/swfoptions/slides_layout_options/) | Mengambil atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](/slides/python-net/id/aspose.slides.export/islideslayoutoptions).<br/>            Properti ini tidak mendukung penetapan objek tipe [`HandoutLayoutingOptions`](/slides/python-net/id/aspose.slides.export/handoutlayoutingoptions) |

### Lihat Juga
* kelas [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)
* kelas [`SwfOptions`](/slides/python-net/id/aspose.slides.export/swfoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)