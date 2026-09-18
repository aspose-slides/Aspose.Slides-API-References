---
title: ChartData class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/
---
## ChartData sınıfı

Bir grafik çizimi için kullanılan verileri temsil eder.

ChartData türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/tr/aspose.slides.charts/chartdata/chart_data_workbook/) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır.<br/>            Yalnızca okunur [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/tr/aspose.slides.charts/chartdata/series/) | Serileri alır.<br/>            Yalnızca okunur [`IChartSeriesCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/tr/aspose.slides.charts/chartdata/series_groups/) | Seri gruplarını alır.<br/>            Yalnızca okunur [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories/) | Birincil kategorileri (veya [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği false ise birincil ve ikincil kategorileri birlikte) alır.<br/>            Yalnızca okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories/) | False ise [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) özelliği None döndürür ve [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır.<br/>            True ise [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) özelliğindeki veri ikincil seriler için, [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri ise birincil seriler için kullanılır.<br/>            Okunur/yazılabilir **bool**. |
| [`secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories/) | [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği true ise ikincil kategorileri alır.<br/>            Yalnızca okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/data_source_type/) | Harici veri kaynağı ise harici çalışma kitabı yolunu temsil eder, aksi takdirde None. |
| [`external_workbook_path`](/slides/python-net/tr/aspose.slides.charts/chartdata/external_workbook_path/) | Grafiğin veri kaynağını temsil eder |
| [`embedded_workbook_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/embedded_workbook_type/) | Gömülü çalışma kitabının tipini alır.<br/>            [`WorkbookType.NOT_DEFINED`](/slides/python-net/tr/aspose.slides.charts/workbooktype/NOT_DEFINED) döndürür eğer [`ChartData.data_source_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/tr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Yalnızca okunur [`WorkbookType`](/slides/python-net/tr/aspose.slides.charts/workbooktype). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/tr/aspose.slides.charts/chartdata/set_external_workbook/#str) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/tr/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [`read_workbook_stream(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/read_workbook_stream/#) | Dahili barındırılan Excel çalışma kitabını bir akıma yazar. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/tr/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Dahili barındırılan Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır. |
| [`get_range(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/get_range/#) | Grafik veri aralığını alır. |
| [`set_range(self, formula)`](/slides/python-net/tr/aspose.slides.charts/chartdata/set_range/#str) | Grafik veri aralığını ayarla. Seri ve kategoriler yeni veri aralığına göre güncellenecek.<br/>            Eğer veri aralığındaki seri sayısı grafik verisindeki seri sayısından büyükse, mevcut koleksiyondaki son seriye aynı tipe sahip ek seriler koleksiyonun sonuna eklenecek. |
| [`switch_row_column(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/switch_row_column/#) | Veriyi eksenler arasında değiştir.<br/>            X ekseninde grafiklenen veri Y eksenine taşınacak ve tersine. |

### İlgili
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)