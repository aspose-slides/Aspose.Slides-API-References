---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/
---
## IChartData sınıf

Bir grafik çizimi için kullanılan verileri temsil eder.

IChartData türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/tr/aspose.slides.charts/ichartdata/chart_data_workbook/) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır.<br/>            Yalnızca okuma [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/tr/aspose.slides.charts/ichartdata/series/) | Serileri alır.<br/>            Yalnızca okuma [`IChartSeriesCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/tr/aspose.slides.charts/ichartdata/series_groups/) | Seri gruplarını alır.<br/>            Yalnızca okuma [`IChartSeriesGroupCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories/) | Birincil kategorileri alır (veya [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği false ise birincil ve ikincil kategorileri birlikte alır).<br/>            Yalnızca okuma [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories/) | False ise [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliği None döndürür ve [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır.<br/>            True ise [`IChartData.secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories) özelliğindeki veri ikincil seriler için, [`IChartData.categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/categories) özelliğindeki veri ise birincil seriler için kullanılır.<br/>            Okuma/Yazma **bool**. |
| [`secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/secondary_categories/) | [`IChartData.use_secondary_categories`](/slides/python-net/tr/aspose.slides.charts/ichartdata/use_secondary_categories) özelliği true ise ikincil kategorileri alır.<br/>            Yalnızca okuma [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/tr/aspose.slides.charts/ichartdata/data_source_type/) | Grafiğin veri kaynağını temsil eder |
| [`external_workbook_path`](/slides/python-net/tr/aspose.slides.charts/ichartdata/external_workbook_path/) | Veri kaynağı dışsal ise dış çalışma kitabı yolunu temsil eder, aksi takdirde None |
| [`embedded_workbook_type`](/slides/python-net/tr/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Gömülü çalışma kitabının türünü alır.<br/>            [`IChartData.data_source_type`](/slides/python-net/tr/aspose.slides.charts/ichartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/tr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ise [`WorkbookType.NOT_DEFINED`](/slides/python-net/tr/aspose.slides.charts/workbooktype/NOT_DEFINED) döndürür.<br/>            Yalnızca okuma [`WorkbookType`](/slides/python-net/tr/aspose.slides.charts/workbooktype). |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Dış çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Dış çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [`read_workbook_stream(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/read_workbook_stream/#) | İçeride bulunan Excel çalışma kitabını bellek içi bir akışa yazar. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | İçeride bulunan Excel çalışma kitabını kullanıcı tarafından belirlenen değerle başlatır. |
| [`set_range(self, formula)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/set_range/#str) | Grafik veri aralığını ayarlar. Seri ve kategoriler yeni veri aralığına göre güncellenecektir.<br/>            Veri aralığındaki seri sayısı grafik verisindeki seri sayısından fazla ise mevcut koleksiyondaki son seriye aynı türde ek seriler koleksiyonun sonuna eklenecektir. |
| [`get_range(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/get_range/#) | Grafik veri aralığını alır. |
| [`switch_row_column(self)`](/slides/python-net/tr/aspose.slides.charts/ichartdata/switch_row_column/#) | Veriyi eksen üzerinde değiştirir.<br/>            X ekseninde çizilen veri Y eksenine, Y ekseninde çizilen veri X eksenine taşınır. |

### Diğerlerine Bakın
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)