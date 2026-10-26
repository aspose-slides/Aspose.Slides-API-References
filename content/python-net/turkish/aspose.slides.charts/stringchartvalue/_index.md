---
title: StringChartValue class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/stringchartvalue/
---
## StringChartValue sınıfı

pptx sunum belgesinde iki şekilde depolanabilen dize değerini temsil eder:
            1) chart ile ilişkili çalışma kitabının hücresi/hücreleri;
            2) düz metin değeri olarak.

**Kalıtım:**[`StringChartValue`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/tr/aspose.slides.charts/basechartvalue)

StringChartValue türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`data_source_type`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue/data_source_type/) | Descendant sınıflarında AsCell, AsCells, AsLiteralString veya AsLiteralDouble <br/>            özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle Data özelliğinin değerinin türünü belirtir.<br/>            Okunur/yazılır [`DataSourceType`](/slides/python-net/tr/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue/data/) | Data nesnesini döndürür veya ayarlar.<br/>            Okunur/yazılır **any**. |
| [`as_cells`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue/as_cells/) | Null değer atamasına izin verilmez.<br/>            Döndürülen değer her zaman None değildir.<br/>            Okunur/yazılır [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue/as_literal_string/) | Değeri düz metin olarak döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Belirtilen hücreden değeri ayarlar. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Eğer DataSourceType özelliği DataSourceType.Worksheet ise bu yöntem, dize verisini temsil eden çalışma kitabındaki hücrelerin adresini döndürür<br/>            . Aksi takdirde boş dize döndürür. |

### Ayrıca Bakınız
* sınıf [`BaseChartValue`](/slides/python-net/tr/aspose.slides.charts/basechartvalue)
* sınıf [`StringChartValue`](/slides/python-net/tr/aspose.slides.charts/stringchartvalue)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)