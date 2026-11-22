---
title: DataLabel class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/datalabel/
---
## kelas DataLabel

Mewakili label seri.

Tipe DataLabel mengekspos anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/id/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Membuat instance baru dari kelas DataLabel. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`chart`](/slides/python-net/id/aspose.slides.charts/datalabel/chart/) | Mengembalikan chart induk.<br/>            Hanya-baca [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/id/aspose.slides.charts/datalabel/is_visible/) | False berarti label data tidak terlihat (dan semua flag Show*- (ShowValue, ...) menjadi false).<br/>            Hanya-baca **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/id/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Dapat berisi teks terformat kaya. Jika properti ini tidak None maka nilai teks terformat ini menggantikan teks yang dihasilkan otomatis dari label data.<br/>            Teks yang dihasilkan otomatis dari label data berarti teks yang dikelola oleh properti ShowSeriesName, <br/>            ShowValue, ... dan diformat dengan properti TextFormatManager.TextFormat.<br/>            Hanya-baca [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/id/aspose.slides.charts/datalabel/text_format/) | Mengembalikan format teks.<br/>            Hanya-baca [`IChartTextFormat`](/slides/python-net/id/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/id/aspose.slides.charts/datalabel/x/) | Mengembalikan atau mengatur koordinat x judul sebagai fraksi lebar chart.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides.charts/datalabel/y/) | Mengembalikan atau mengatur koordinat y judul sebagai fraksi tinggi chart.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides.charts/datalabel/width/) | Mengembalikan atau mengatur lebar judul sebagai fraksi lebar chart.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides.charts/datalabel/height/) | Mengembalikan atau mengatur tinggi judul sebagai fraksi tinggi chart.<br/>            Baca/tulis **float**. |
| [`right`](/slides/python-net/id/aspose.slides.charts/datalabel/right/) | Kanan.<br/>            Hanya-baca **float**. |
| [`bottom`](/slides/python-net/id/aspose.slides.charts/datalabel/bottom/) | Bawah.<br/>            Hanya-baca **float**. |
| [`data_label_format`](/slides/python-net/id/aspose.slides.charts/datalabel/data_label_format/) | Mengembalikan format label data.<br/>            Hanya-baca [`IDataLabelFormat`](/slides/python-net/id/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/id/aspose.slides.charts/datalabel/value_from_cell/) | Mendapatkan atau mengatur sel data workbook. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true. |
| [`label_shape_type`](/slides/python-net/id/aspose.slides.charts/datalabel/label_shape_type/) | Mendapatkan atau mengatur tipe bentuk label data.<br/>             Mengembalikan [`ShapeType.NOT_DEFINED`](/slides/python-net/id/aspose.slides/shapetype/NOT_DEFINED) jika tidak ada bentuk yang didefinisikan. |
| [`actual_x`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_x/) | Menentukan lokasi x aktual (kiri) elemen chart relatif terhadap sudut kiri atas chart.<br/>            Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`actual_y`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_y/) | Menentukan atas aktual elemen chart relatif terhadap sudut kiri atas chart.<br/>            Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`actual_width`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_width/) | Menentukan lebar aktual elemen chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`actual_height`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_height/) | Menentukan tinggi aktual elemen chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`slide`](/slides/python-net/id/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/datalabel/presentation/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`hide(self)`](/slides/python-net/id/aspose.slides.charts/datalabel/hide/#) | Membuat label data tersembunyi dengan mengatur semua flag Show*- (ShowValue, ...) ke keadaan false.<br/>            IsVisible akan menjadi false setelah ini. |
| [`get_actual_label_text(self)`](/slides/python-net/id/aspose.slides.charts/datalabel/get_actual_label_text/#) | Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/id/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inisialisasi TextFrameForOverriding dengan teks pada parameter "text".<br/>            Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya. |

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)