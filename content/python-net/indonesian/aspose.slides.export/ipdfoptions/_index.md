---
title: IPdfOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/ipdfoptions/
---
## kelas IPdfOptions

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Pdf.

Tipe IPdfOptions menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`text_compression`](/slides/python-net/id/aspose.slides.export/ipdfoptions/text_compression/) | Menentukan tipe kompresi yang digunakan untuk semua konten teks dalam dokumen.<br/>            Baca/tulis [`PdfTextCompression`](/slides/python-net/id/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/id/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis.<br/>            Jika diatur ke **bool**.true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil.<br/>            Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang mahal dan memakan tambahan RAM, dan opsi ini secara default **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/id/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Benar untuk menyematkan font TrueType untuk karakter ASCII 32-127.<br/>            Font untuk kode karakter lebih dari 127 selalu disematkan.<br/>            Baca/tulis **bool**. |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Default adalah `false`. |
| [`additional_common_font_families`](/slides/python-net/id/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Mengembalikan atau mengatur array nama-nama keluarga font yang didefinisikan pengguna yang harus dianggap umum oleh Aspose.Slides.<br/>            Baca/tulis **str**[]. |
| [`embed_full_fonts`](/slides/python-net/id/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan.<br/>            Baca/tulis **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/id/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Menunjukkan apakah teks harus di rasterkan sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal.<br/>            Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu.<br/>            Baca/tulis **bool**. |
| [`jpeg_quality`](/slides/python-net/id/aspose.slides.export/ipdfoptions/jpeg_quality/) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF.<br/>            Baca/tulis **int**. |
| [`compliance`](/slides/python-net/id/aspose.slides.export/ipdfoptions/compliance/) | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan.<br/>            Baca/tulis [`PdfCompliance`](/slides/python-net/id/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/id/aspose.slides.export/ipdfoptions/password/) | Mengatur kata sandi pengguna untuk melindungi dokumen PDF. <br/>            Baca/tulis **str**. |
| [`access_permissions`](/slides/python-net/id/aspose.slides.export/ipdfoptions/access_permissions/) | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka<br/>            dengan akses pengguna. Lihat [`PdfAccessPermissions`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/id/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Benar untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG.<br/>            Baca/tulis **bool**. |
| [`sufficient_resolution`](/slides/python-net/id/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF.<br/>            <br/>Properti memengaruhi ukuran file, waktu ekspor, dan kualitas gambar.<br/><br/><br/>Nilai default adalah **96** .<br/><br/><br/>            Baca/tulis **float**. |
| [`draw_slides_frame`](/slides/python-net/id/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Benar untuk menggambar bingkai hitam di sekitar setiap slide.<br/>             Baca/tulis **bool**. |
| [`slides_layout_options`](/slides/python-net/id/aspose.slides.export/ipdfoptions/slides_layout_options/) | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](/slides/python-net/id/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/id/aspose.slides.export/ipdfoptions/image_transparent_color/) | Mengambil atau mengatur warna transparan gambar. |
| [`apply_image_transparent`](/slides/python-net/id/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Menerapkan warna transparan yang ditentukan ke gambar jika `true`. |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/ipdfoptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Baca-saja [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/id/aspose.slides.export/ipdfoptions/include_ole_data/) | Benar untuk mengonversi semua data OLE dari presentasi menjadi file yang disematkan dalam PDF yang dihasilkan.<br/>            Baca/tulis **bool**. |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)