---
title: PdfOptions class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides.export/pdfoptions/
---
## PdfOptions kelas

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Pdf.

**Inheritance:**[`PdfOptions`](/slides/python-net/id/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)

The PdfOptions type exposes the following members:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/pdfoptions/__init__/#) | Konstruktor default. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/pdfoptions/warning_callback/) | Mengembalikan atau mengatur sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dihentikan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/pdfoptions/progress_callback/) | Mewakili objek callback untuk pembaruan progres penyimpanan dalam persentase.<br/>            Lihat [`IProgressCallback`](/slides/python-net/id/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/pdfoptions/default_regular_font/) | Mengembalikan atau mengatur font yang digunakan jika font sumber tidak ditemukan.<br/>            Baca-tulis **str**. |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/pdfoptions/gradient_style/) | Mengembalikan atau mengatur gaya visual gradient.<br/>            Baca/tulis [`GradientStyle`](/slides/python-net/id/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/pdfoptions/skip_java_script_links/) | Menentukan apakah akan melewati hyperlink dengan panggilan JavaScript saat menyimpan presentasi.<br/>            Baca/tulis **bool**. Nilai default adalah **false**. |
| [`slides_layout_options`](/slides/python-net/id/aspose.slides.export/pdfoptions/slides_layout_options/) | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](/slides/python-net/id/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/pdfoptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Baca-saja [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/pdfoptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Nilai default adalah `false`. |
| [`text_compression`](/slides/python-net/id/aspose.slides.export/pdfoptions/text_compression/) | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen.<br/>            Baca/tulis [`PdfTextCompression`](/slides/python-net/id/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/id/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Menunjukkan apakah kompresi paling efektif (alih-alih yang default) untuk setiap gambar harus dipilih <br/>            secara otomatis. Jika diatur ke **bool**.true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil. <br/>            Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang mahal dan membutuhkan <br/>            tambahan RAM, dan opsi ini **bool**.false secara default. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/id/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Menentukan apakah Aspose.Slides akan menyematkan font umum untuk teks ASCII (rentang kode 33..127).<br/>            Font untuk kode karakter lebih besar dari 127 selalu disematkan.<br/>            Daftar font umum mencakup 14 font dasar PDF dan font tambahan yang ditentukan pengguna.<br/>            Baca/tulis **bool**. |
| [`additional_common_font_families`](/slides/python-net/id/aspose.slides.export/pdfoptions/additional_common_font_families/) | Mengembalikan atau mengatur array nama keluarga font yang ditentukan pengguna yang harus dianggap umum oleh Aspose.Slides.<br/>            Baca/tulis **str**[]. |
| [`embed_full_fonts`](/slides/python-net/id/aspose.slides.export/pdfoptions/embed_full_fonts/) | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan.<br/>            Baca/tulis **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/id/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Menunjukkan apakah teks harus diraster menjadi bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal.<br/>            Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu.<br/>            Baca/tulis **bool**. |
| [`jpeg_quality`](/slides/python-net/id/aspose.slides.export/pdfoptions/jpeg_quality/) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF.<br/>            Baca/tulis **int**. |
| [`compliance`](/slides/python-net/id/aspose.slides.export/pdfoptions/compliance/) | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan.<br/>            Baca/tulis [`PdfCompliance`](/slides/python-net/id/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/id/aspose.slides.export/pdfoptions/password/) | Mengatur kata sandi pengguna untuk melindungi dokumen PDF.<br/>            Baca/tulis **str**. |
| [`access_permissions`](/slides/python-net/id/aspose.slides.export/pdfoptions/access_permissions/) | Berisi serangkaian flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna.<br/>            Lihat [`PdfAccessPermissions`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/id/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG.<br/>            Baca/tulis **bool**. |
| [`sufficient_resolution`](/slides/python-net/id/aspose.slides.export/pdfoptions/sufficient_resolution/) | Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF.<br/>            <br/>Properti memengaruhi ukuran file, waktu ekspor, dan kualitas gambar.<br/><br/><br/>Nilai default adalah **96**.<br/><br/><br/>            Baca/tulis **float**. |
| [`draw_slides_frame`](/slides/python-net/id/aspose.slides.export/pdfoptions/draw_slides_frame/) | Benar untuk menggambar bingkai hitam di sekitar setiap slide.<br/>             Baca/tulis **bool**. |
| [`image_transparent_color`](/slides/python-net/id/aspose.slides.export/pdfoptions/image_transparent_color/) | Mengambil atau mengatur warna transparan gambar. |
| [`apply_image_transparent`](/slides/python-net/id/aspose.slides.export/pdfoptions/apply_image_transparent/) | Menerapkan warna transparan yang ditentukan ke gambar jika `true`. |
| [`include_ole_data`](/slides/python-net/id/aspose.slides.export/pdfoptions/include_ole_data/) | Benar untuk mengonversi semua data OLE dari presentasi menjadi file tersemat dalam PDF yang dihasilkan.<br/>            Baca/tulis **bool**. |


### Lihat Juga
* kelas [`PdfOptions`](/slides/python-net/id/aspose.slides.export/pdfoptions)
* kelas [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* pustaka [`Aspose.Slides`](/slides/python-net)