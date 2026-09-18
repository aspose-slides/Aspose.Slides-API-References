---
title: ExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook sınıfı

Genel kullanım için Excel verilerine erişim sağlayan bir çalışma kitabını temsil eder.

ExcelDataWorkbook türü aşağıdaki üyeleri sağlar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/__init__/#str) | Belirtilen dosya yolunu kullanarak yeni bir örnek başlatır. |
| [`__init__(self, stream)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Sağlanan akışı kullanarak sınıfın yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Belirtilen çalışma sayfasından, dizini ve hücre koordinatlarını kullanarak bir hücre alır. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Belirtilen çalışma sayfasından, adı ve hücre koordinatlarını kullanarak bir hücre alır. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Belirtilen çalışma sayfasından, dizini ve Excel tarzı hücre adı (örn. "B2") kullanarak bir hücre alır. |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Belirtilen çalışma sayfasından, Excel tarzı hücre adı (örn. "B2") kullanarak bir hücre alır. |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Belirtilen formülle eşleşen hücrelerin bir koleksiyonunu çalışma kitabından alır. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Excel çalışma kitabının belirtilen çalışma sayfasındaki tüm grafiklerin dizin ve adlarını içeren bir sözlük alır. |
| [`get_worksheet_names(self)`](/slides/python-net/tr/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını alır. |


### Ayrıca Bakınız
* modül [`aspose.slides.excel`](/slides/python-net/tr/aspose.slides.excel)
* kütüphane [`Aspose.Slides`](/slides/python-net)