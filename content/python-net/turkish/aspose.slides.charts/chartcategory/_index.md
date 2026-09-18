---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartcategory/
---
## ChartCategory sınıfı

Grafik kategorilerini temsil eder.

ChartCategory türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`use_cell`](/slides/python-net/tr/aspose.slides.charts/chartcategory/use_cell/) | Eğer true ise AsCell özelliği geçerlidir. Başka bir deyişle, worksheet kategori <br/>            depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir).<br/>            Eğer false ise AsLiteral özelliği geçerlidir. Başka bir deyişle, worksheet kategori <br/>            depolamak için KULLANILMAZ (ve bu durumda çok seviyeli kategoriler desteklenmez).<br/>            Salt okunur **bool**. |
| [`as_cell`](/slides/python-net/tr/aspose.slides.charts/chartcategory/as_cell/) | IChartDataCell nesnesini döndürür veya ayarlar.<br/>            Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır.<br/>            Okunur/yazılır [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/tr/aspose.slides.charts/chartcategory/as_literal/) | AsLiteral nesnesini döndürür veya ayarlar.<br/>            Okunur/yazılır **any**. |
| [`value`](/slides/python-net/tr/aspose.slides.charts/chartcategory/value/) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder.<br/>            UseCell false ise bu özellik AsLiteral özelliğini temsil eder.<br/>            Okunur/yazılır **any**. |
| [`grouping_levels`](/slides/python-net/tr/aspose.slides.charts/chartcategory/grouping_levels/) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri.<br/>            Çok seviyeli kategori birden fazla gruplama seviyesi içerir.<br/>            Gruplama seviyeleri indekslemesi sıfır tabanlıdır.<br/>            Salt okunur [`IChartCategoryLevelsManager`](/slides/python-net/tr/aspose.slides.charts/ichartcategorylevelsmanager). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/chartcategory/remove/#) | Kategoriyi grafikten kaldırır. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)