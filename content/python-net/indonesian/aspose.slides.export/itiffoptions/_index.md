---
title: ITiffOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/itiffoptions/
---
## ITiffOptions kelas

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format TIFF.

Tipe ITiffOptions memperlihatkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`image_size`](/slides/python-net/id/aspose.slides.export/itiffoptions/image_size/) | Menentukan ukuran gambar TIFF yang dihasilkan.<br/>            Nilai default adalah 0x0, yang berarti ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi.<br/>            Baca/tulis [`Size`](/slides/python-net/id/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/id/aspose.slides.export/itiffoptions/dpi_x/) | Menentukan resolusi horizontal dalam titik per inci.<br/>            Baca/tulis **int**. |
| [`dpi_y`](/slides/python-net/id/aspose.slides.export/itiffoptions/dpi_y/) | Menentukan resolusi vertikal dalam titik per inci.<br/>            Baca/tulis **int**. |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/itiffoptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Nilai default adalah `false`. |
| [`compression_type`](/slides/python-net/id/aspose.slides.export/itiffoptions/compression_type/) | Menentukan jenis kompresi.<br/>            Baca/tulis [`TiffCompressionTypes`](/slides/python-net/id/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/id/aspose.slides.export/itiffoptions/pixel_format/) | Menentukan format piksel untuk gambar yang dihasilkan.<br/>            Baca/tulis [`ImagePixelFormat`](/slides/python-net/id/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/id/aspose.slides.export/itiffoptions/slides_layout_options/) | Mendapatkan atau mengatur mode di mana slide ditempatkan pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](/slides/python-net/id/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/id/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih.<br/>            Opsi ini hanya akan diterapkan jika [`ITiffOptions.compression_type`](/slides/python-net/id/aspose.slides.export/itiffoptions/compression_type) <br/>            diatur ke [`TiffCompressionTypes.CCITT4`](/slides/python-net/id/aspose.slides.export/tiffcompressiontypes/CCITT4) atau [`TiffCompressionTypes.CCITT3`](/slides/python-net/id/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Baca/tulis [`BlackWhiteConversionMode`](/slides/python-net/id/aspose.slides.export/blackwhiteconversionmode).<br/>            Nilai default adalah [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/id/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/itiffoptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Baca-saja [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)