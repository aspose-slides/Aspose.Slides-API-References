---
title: ErrorBarsFormat class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat kelas

Mewakili error bars dari seri diagram. Nilai kustom ErrorBars berada di IChartDataPointCollection
            (di properti [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Tipe ErrorBarsFormat mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`type`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/type/) | Mendapatkan atau mengatur tipe error bars. <br/>            Baca/tulis [`ErrorBarType`](/slides/python-net/id/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/value_type/) | Mewakili cara-cara yang mungkin untuk menentukan panjang error bars. <br/>            Jika tipe nilai kustom, gunakan properti [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) dari titik data spesifik dalam koleksi DataPoints pada seri.<br/>            Jika tipe nilai Fixed, Percentage, atau StandardDeviation, gunakan properti Value untuk menentukan nilai.  <br/>            Baca/tulis [`ErrorBarValueType`](/slides/python-net/id/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/has_end_cap/) | Menentukan bahwa ujung penutup tidak digambar pada error bars.<br/>            Baca/tulis **bool**. |
| [`value`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/value/) | Mendapatkan atau mengatur nilai yang digunakan dengan tipe nilai Fixed, Percentage, dan StandardDeviation untuk menentukan panjang error bars. <br/>            Pada kasus lain akan mengembalikan NaN.<br/>            Baca/tulis **float**. |
| [`format`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/format/) | Mewakili format error bars.<br/>            Baca/tulis [`IFormat`](/slides/python-net/id/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/chart/) | Mengembalikan diagram induk.<br/>            Baca-saja [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/is_visible/) | Mendapatkan atau mengatur visibilitas Error Bars.<br/>            Baca/tulis **bool**. |
| [`slide`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/errorbarsformat/presentation/) |  |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)