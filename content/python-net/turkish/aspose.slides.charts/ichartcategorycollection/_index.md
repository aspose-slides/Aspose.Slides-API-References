---
title: IChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection sınıfı

[`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory) koleksiyonunu temsil eder

The IChartCategoryCollection type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`use_cells`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/use_cells/) | Eğer true ise worksheet kategorileri depolamak için kullanılır (bu durumda çok seviyeli kategoriler desteklenir).<br/>            Eğer false ise worksheet değerleri depolamak için KULLANILMAZ (ve bu durumda çok seviyeli kategoriler desteklenmez).<br/>            Okunur/yazılır **bool**. |
| [`grouping_level_count`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Kullanılan kategori gruplama seviyelerinin sayısını döndürür.<br/>            Çok seviyeli kategoriler için birden fazla olur.<br/>            Salt okunur **int**. |

Belirtilen dizindeki öğeyi alır.

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Eğer kategori koleksiyonda mevcutsa, onu döndürür. Aksi halde [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) kaynağından yeni bir chart category oluşturur ve koleksiyona ekler. |
| [`add(self, value)`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/add/#any) | Değerden yeni bir [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory) oluşturur ve koleksiyona ekler. |
| [`index_of(self, value)`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Belirtilen [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory) içinde arama yapar ve tüm Collection içinde ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [`remove(self, value)`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Belirtilen değeri kaldırır. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Verilen indeksteki öğeyi kaldırır. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection/clear/#) | Koleksiyondaki tüm öğeleri kaldırır. |

### Ayrıca Bakınız
* sınıf [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)