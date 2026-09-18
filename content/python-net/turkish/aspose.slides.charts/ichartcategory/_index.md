---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartcategory/
---
## IChartCategory sınıfı

Grafik kategorilerini temsil eder.

IChartCategory türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`use_cell`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/use_cell/) | true ise AsCell özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori <br/>            depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir).<br/>            false ise AsLiteral özelliği geçerlidir. Başka bir deyişle, çalışma sayfası <br/>            kategori depolamak için KULLANILMAZ (ve bu durumda çok seviyeli kategoriler desteklenmez).<br/>            Yalnızca okuma **bool**. |
| [`as_cell`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/as_cell/) | IChartDataCell nesnesini döndürür veya ayarlar.<br/>            Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır.<br/>            Okunabilir/Yazılabilir [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/as_literal/) | UseCell false ise AsLiteral döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir **any**. |
| [`value`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/value/) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder.<br/>            UseCell false ise bu özellik AsLiteral özelliğini temsil eder.<br/>            Okunabilir/Yazılabilir **any**. |
| [`grouping_levels`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/grouping_levels/) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri.<br/>            Çok seviyeli kategori birden fazla gruplama seviyesi içerir.<br/>            Gruplama seviyelerinin dizinlemesi sıfır tabanlıdır.<br/>            Yalnızca okuma [`IChartCategoryLevelsManager`](/slides/python-net/tr/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metodlar

| Metod | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/remove/#) | Kategoriyi grafikten kaldırır. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)