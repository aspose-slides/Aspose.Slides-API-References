---
title: Trendline class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/trendline/
---
## Trendline kelas

Kelas mewakili garis tren dari seri diagram

The Trendline type exposes the following members:

## Properti

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/id/aspose.slides.charts/trendline/trendline_name/) | Mendapatkan atau mengatur nama trendline.<br/>            Baca/tulis **str**. |
| [`trendline_type`](/slides/python-net/id/aspose.slides.charts/trendline/trendline_type/) | Mendapatkan atau mengatur tipe trend line.<br/>            Baca/tulis [`TrendlineType`](/slides/python-net/id/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/id/aspose.slides.charts/trendline/format/) | Mewakili format trend line.<br/>            Baca/tulis [`IFormat`](/slides/python-net/id/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/id/aspose.slides.charts/trendline/backward/) | Menentukan jumlah kategori (atau unit pada diagram sebar) yang trend line diperluas sebelum<br/>            data untuk seri yang sedang ditrend. Pada diagram sebar dan non-sebar, nilai harus berupa non-negatif<br/>            apapun.<br/>            Baca/tulis **float**. |
| [`forward`](/slides/python-net/id/aspose.slides.charts/trendline/forward/) | Menentukan jumlah kategori (atau unit pada diagram sebar) yang trendline diperluas setelah<br/>            data untuk seri yang sedang ditrend. Pada diagram sebar dan non-sebar, nilai harus berupa non-negatif<br/>            apapun.<br/>            Baca/tulis **float**. |
| [`intercept`](/slides/python-net/id/aspose.slides.charts/trendline/intercept/) | Menentukan nilai di mana trendline melintasi sumbu y. Properti ini hanya didukung<br/>            ketika tipe trendline adalah exp, linear, atau poly.<br/>            Baca/tulis **float**. |
| [`display_equation`](/slides/python-net/id/aspose.slides.charts/trendline/display_equation/) | Menentukan bahwa persamaan untuk trendline ditampilkan pada diagram (dalam label yang sama dengan nilai Rsquared).<br/>            Baca/tulis **bool**. |
| [`order`](/slides/python-net/id/aspose.slides.charts/trendline/order/) | Menentukan urutan polynomial trend line. Diabaikan untuk tipe trend line lainnya. Nilai harus antara 2 dan 6.<br/>            Baca/tulis **int**. |
| [`period`](/slides/python-net/id/aspose.slides.charts/trendline/period/) | Menentukan periode trend line untuk moving average trend line. Diabaikan untuk varian trend line lainnya. Nilai harus antara 2 dan 255.<br/>            Baca/tulis **int**. |
| [`display_r_squared_value`](/slides/python-net/id/aspose.slides.charts/trendline/display_r_squared_value/) | Menentukan bahwa nilai R-kuadrat dari trendline ditampilkan pada diagram (dalam label yang sama dengan persamaan).<br/>            Baca/tulis **bool**. |
| [`related_legend_entry`](/slides/python-net/id/aspose.slides.charts/trendline/related_legend_entry/) | Mewakili entri legenda yang terkait dengan trendline ini<br/>            Baca-saja [`ILegendEntryProperties`](/slides/python-net/id/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/id/aspose.slides.charts/trendline/text_frame_for_overriding/) | Dapat berisi teks berformat kaya. Jika properti ini tidak None maka nilai teks berformat ini<br/>            menggantikan teks yang dihasilkan secara otomatis dari label data.<br/>            Teks yang dihasilkan secara otomatis dari label data berarti teks yang dikelola oleh properti ShowSeriesName, <br/>            ShowValue, ... dan diformat dengan properti TextFormatManager.TextFormat.<br/>            Baca-saja [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/id/aspose.slides.charts/trendline/text_format/) | Mengembalikan format teks.<br/>            Baca-saja [`IChartTextFormat`](/slides/python-net/id/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/id/aspose.slides.charts/trendline/chart/) | Mengembalikan diagram induk.<br/>            Baca-saja [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/id/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/trendline/presentation/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/id/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Menginisialisasi TextFrameForOverriding dengan teks pada parameter "text".<br/>            Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya. |


### Lihat Juga
* module [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)