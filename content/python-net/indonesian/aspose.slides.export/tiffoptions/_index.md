---
title: TiffOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/tiffoptions/
---
## TiffOptions class

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format TIFF.

**Warisan:**[`TiffOptions`](/slides/python-net/id/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)

The TiffOptions type exposes the following members:

## Constructors

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/tiffoptions/__init__/#) | Konstruktor default. |

## Properties

| Properti | Deskripsi |
| :- | :- |
| [`warning_callback`](/slides/python-net/id/aspose.slides.export/tiffoptions/warning_callback/) | Mengembalikan atau mengatur sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/id/aspose.slides.export/tiffoptions/progress_callback/) | Mewakili objek callback untuk memperbarui kemajuan penyimpanan dalam persentase.<br/>            Lihat [`IProgressCallback`](/slides/python-net/id/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides.export/tiffoptions/default_regular_font/) | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`gradient_style`](/slides/python-net/id/aspose.slides.export/tiffoptions/gradient_style/) | Mengembalikan atau mengatur gaya visual dari gradien.<br/>            Baca/tulis [`GradientStyle`](/slides/python-net/id/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/id/aspose.slides.export/tiffoptions/skip_java_script_links/) | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi.<br/>            Baca/tulis **bool**. Nilai defaultnya adalah **false**. |
| [`ink_options`](/slides/python-net/id/aspose.slides.export/tiffoptions/ink_options/) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor.<br/>            Baca-saja [`IInkOptions`](/slides/python-net/id/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/id/aspose.slides.export/tiffoptions/show_hidden_slides/) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak.<br/>            Defaultnya adalah `false`. |
| [`image_size`](/slides/python-net/id/aspose.slides.export/tiffoptions/image_size/) | Menentukan ukuran gambar TIFF yang dihasilkan.<br/>            Nilai defaultnya adalah 0x0, yang berarti ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi.<br/>            Baca/tulis **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/id/aspose.slides.export/tiffoptions/dpi_x/) | Menentukan resolusi horizontal dalam titik per inci.<br/>            Baca/tulis **int**. |
| [`dpi_y`](/slides/python-net/id/aspose.slides.export/tiffoptions/dpi_y/) | Menentukan resolusi vertikal dalam titik per inci.<br/>            Baca/tulis **int**. |
| [`compression_type`](/slides/python-net/id/aspose.slides.export/tiffoptions/compression_type/) | Menentukan jenis kompresi.<br/>            Baca/tulis [`TiffCompressionTypes`](/slides/python-net/id/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/id/aspose.slides.export/tiffoptions/pixel_format/) | Menentukan format piksel untuk gambar yang dihasilkan.<br/>            Baca/tulis [`ImagePixelFormat`](/slides/python-net/id/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/id/aspose.slides.export/tiffoptions/slides_layout_options/) | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](/slides/python-net/id/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/id/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih.<br/>            Opsi ini hanya akan diterapkan jika [`TiffOptions.compression_type`](/slides/python-net/id/aspose.slides.export/tiffoptions/compression_type) <br/>            disetel ke [`TiffCompressionTypes.CCITT4`](/slides/python-net/id/aspose.slides.export/tiffcompressiontypes/CCITT4) atau [`TiffCompressionTypes.CCITT3`](/slides/python-net/id/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Baca/tulis [`BlackWhiteConversionMode`](/slides/python-net/id/aspose.slides.export/blackwhiteconversionmode).<br/>            Defaultnya adalah [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/id/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Lihat Juga
* kelas [`SaveOptions`](/slides/python-net/id/aspose.slides.export/saveoptions)
* kelas [`TiffOptions`](/slides/python-net/id/aspose.slides.export/tiffoptions)
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)