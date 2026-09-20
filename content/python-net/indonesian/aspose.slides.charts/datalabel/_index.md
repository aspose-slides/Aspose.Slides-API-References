---
title: DataLabel class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/datalabel/
---
## DataLabel kelas

Mewakili label seri.

Tipe DataLabel menampilkan anggota berikut:

## Konstruktor

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/id/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Membuat instance baru dari kelas DataLabel. |

## Properti

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/id/aspose.slides.charts/datalabel/chart/) | Mengembalikan chart induk.<br/>            Baca-saja [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/id/aspose.slides.charts/datalabel/is_visible/) | False berarti bahwa label data tidak terlihat (dan sehingga semua Show*-flags (ShowValue, ...) adalah false).<br/>            Baca-saja **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/id/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Dapat berisi teks berformat kaya. Jika properti ini tidak None maka nilai teks berformat ini menggantikan teks yang dihasilkan secara otomatis oleh label data.<br/>            Teks yang dihasilkan secara otomatis oleh label data berarti teks yang dikelola oleh properti ShowSeriesName, <br/>            ShowValue, ... dan diformat dengan properti TextFormatManager.TextFormat.<br/>            Baca-saja [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/id/aspose.slides.charts/datalabel/text_format/) | Mengembalikan format teks.<br/>            Baca-saja [`IChartTextFormat`](/slides/python-net/id/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/id/aspose.slides.charts/datalabel/x/) | Mengembalikan atau mengatur koordinat x judul sebagai fraksi lebar chart.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides.charts/datalabel/y/) | Mengembalikan atau mengatur koordinat y judul sebagai fraksi tinggi chart.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides.charts/datalabel/width/) | Mengembalikan atau mengatur lebar judul sebagai fraksi lebar chart.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides.charts/datalabel/height/) | Mengembalikan atau mengatur tinggi judul sebagai fraksi tinggi chart.<br/>            Baca/tulis **float**. |
| [`right`](/slides/python-net/id/aspose.slides.charts/datalabel/right/) | Kanan.<br/>            Baca-saja **float**. |
| [`bottom`](/slides/python-net/id/aspose.slides.charts/datalabel/bottom/) | Bawah.<br/>            Baca-saja **float**. |
| [`data_label_format`](/slides/python-net/id/aspose.slides.charts/datalabel/data_label_format/) | Mengembalikan format label data.<br/>            Baca-saja [`IDataLabelFormat`](/slides/python-net/id/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/id/aspose.slides.charts/datalabel/value_from_cell/) | Mendapatkan atau menetapkan sel data buku kerja. Diterapkan jika properti IDataLabelFormat.ShowLabelValueFromCell bernilai true. |
| [`actual_x`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_x/) | Menentukan lokasi x aktual (kiri) elemen chart relatif pada sudut kiri atas chart.<br/>            Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`actual_y`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_y/) | Menentukan posisi atas aktual elemen chart relatif pada sudut kiri atas chart.<br/>            Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`actual_width`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_width/) | Menentukan lebar aktual elemen chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`actual_height`](/slides/python-net/id/aspose.slides.charts/datalabel/actual_height/) | Menentukan tinggi aktual elemen chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. <br/>            Baca **float**. |
| [`slide`](/slides/python-net/id/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/datalabel/presentation/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/id/aspose.slides.charts/datalabel/hide/#) | Membuat label data tersembunyi dengan mengatur semua Show*-flags (ShowValue, ...) ke keadaan false.<br/>            IsVisible akan menjadi false setelah ini. |
| [`get_actual_label_text(self)`](/slides/python-net/id/aspose.slides.charts/datalabel/get_actual_label_text/#) | Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/id/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inisialisasi TextFrameForOverriding dengan teks dalam parameter "text".<br/>            Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)