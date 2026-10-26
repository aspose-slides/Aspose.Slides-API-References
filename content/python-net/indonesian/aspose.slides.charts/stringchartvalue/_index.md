---
title: StringChartValue class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides.charts/stringchartvalue/
---
## StringChartValue kelas

Mewakili nilai string yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara:
1) dalam sel/sel-sel workbook yang terkait dengan chart;
2) sebagai nilai literal.

**Warisan:**[`StringChartValue`](/slides/python-net/id/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/id/aspose.slides.charts/basechartvalue)

Tipe StringChartValue mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`data_source_type`](/slides/python-net/id/aspose.slides.charts/stringchartvalue/data_source_type/) | Menentukan apakah AsCell, AsCells, AsLiteralString, atau AsLiteralDouble <br/>            properti sebenarnya ada pada turunan. Dengan kata lain, menentukan jenis <br/>            nilai dari properti Data.<br/>            Baca/tulis [`DataSourceType`](/slides/python-net/id/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/id/aspose.slides.charts/stringchartvalue/data/) | Mengembalikan atau mengatur objek Data.<br/>            Baca/tulis **any**. |
| [`as_cells`](/slides/python-net/id/aspose.slides.charts/stringchartvalue/as_cells/) | Penetapan nilai null tidak diizinkan.<br/>            Nilai yang dikembalikan selalu bukan None.<br/>            Baca/tulis [`IChartCellCollection`](/slides/python-net/id/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/id/aspose.slides.charts/stringchartvalue/as_literal_string/) | Mengembalikan atau mengatur nilai sebagai string literal.<br/>            Baca/tulis **str**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/id/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Mengatur nilai dari sel yang ditentukan. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/id/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Jika properti DataSourceType adalah DataSourceType.Worksheet maka metode ini mengembalikan alamat<br/>            sel-sel dalam workbook yang mewakili data string. Jika tidak, mengembalikan<br/>            string kosong. |

### Lihat Juga
* kelas [`BaseChartValue`](/slides/python-net/id/aspose.slides.charts/basechartvalue)
* kelas [`StringChartValue`](/slides/python-net/id/aspose.slides.charts/stringchartvalue)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)