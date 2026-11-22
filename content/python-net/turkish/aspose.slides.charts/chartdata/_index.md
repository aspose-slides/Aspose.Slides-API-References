---
title: ChartData class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/
---
## ChartData sınıfı

Bir grafik çizimi için kullanılan verileri temsil eder.

ChartData türü aşağıdaki üyelere sahiptir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/tr/aspose.slides.charts/chartdata/chart_data_workbook/) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır.<br/>            Salt okunur [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/tr/aspose.slides.charts/chartdata/series/) | Serileri alır.<br/>            Salt okunur [`IChartSeriesCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/tr/aspose.slides.charts/chartdata/series_groups/) | Seri gruplarını alır.<br/>            Salt okunur [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories/) | Birincil kategorileri (veya [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği false ise birincil ve ikincil kategorileri birlikte) alır.<br/>            Salt okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories/) | Eğer false ise [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) özelliği None döndürür ve [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır.<br/>            Eğer true ise [`ChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories) özelliğindeki veri ikincil seriler için, [`ChartData.categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/categories) özelliğindeki veri ise birincil seriler için kullanılır.<br/>            Okunur/Yazılır **bool**. |
| [`secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/secondary_categories/) | [`ChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/chartdata/use_secondary_categories) özelliği true ise ikincil kategorileri alır.<br/>            Salt okunur [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/data_source_type/) | Harici veri kaynağı ise dış çalışma kitabı yolunu temsil eder, aksi takdirde None |
| [`external_workbook_path`](/slides/python-net/tr/aspose.slides.charts/chartdata/external_workbook_path/) | Grafiğin veri kaynağını temsil eder |
| [`embedded_workbook_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/embedded_workbook_type/) | Yerleşik çalışma kitabının türünü alır.<br/>            [`ChartData.data_source_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/tr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ise [`WorkbookType.NOT_DEFINED`](/slides/python-net/tr/aspose.slides.charts/workbooktype/NOT_DEFINED) döndürür.<br/>            Salt okunur [`WorkbookType`](/slides/python-net/tr/aspose.slides.charts/workbooktype). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/tr/aspose.slides.charts/chartdata/set_external_workbook/#str) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/tr/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [`read_workbook_stream(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/read_workbook_stream/#) | İçeride bulunan Excel çalışma kitabını bir akıma yazar. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/tr/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Kullanıcı tarafından belirtilen değerle içerdeki Excel çalışma kitabını başlatır. |
| [`get_range(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/get_range/#) | Grafik veri aralığını alır. |
| [`set_range(self, formula)`](/slides/python-net/tr/aspose.slides.charts/chartdata/set_range/#str) | Grafik veri aralığını ayarlar. Seriler ve kategoriler yeni veri aralığına göre güncellenecektir.<br/>            Veri aralığındaki seri sayısı grafik verisindeki seri sayısından fazla ise mevcut koleksiyondaki son serinin aynı türünde ek seri koleksiyonun sonuna eklenecektir. |
| [`refresh_data(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/refresh_data/#) | Kaynak çalışma kitabından yeniden yükleyerek grafik verilerini yeniler. |
| [`switch_row_column(self)`](/slides/python-net/tr/aspose.slides.charts/chartdata/switch_row_column/#) | Verileri eksenler arasında değiştirir.<br/>            X ekseninde çizilen veri Y eksenine taşınır ve tersine. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)