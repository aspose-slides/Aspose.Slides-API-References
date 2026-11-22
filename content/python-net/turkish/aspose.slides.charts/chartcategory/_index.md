---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartcategory/
---
## ChartCategory sınıf

Grafik kategorilerini temsil eder.

ChartCategory türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`use_cell`](/slides/python-net/tr/aspose.slides.charts/chartcategory/use_cell/) | Eğer true ise AsCell property geçerlidir. Başka bir deyişle, worksheet kategori depolamak için kullanılır <br/>            (bu durumda çok seviyeli bir kategori desteklenir).<br/>            Eğer false ise AsLiteral property geçerlidir. Başka bir deyişle, worksheet KATEGORİ DEPOLAMAK İÇİN KULLANILMAZ <br/>            (ve bu durumda çok seviyeli kategoriler desteklenmez).<br/>            Yalnızca okunabilir **bool**. |
| [`as_cell`](/slides/python-net/tr/aspose.slides.charts/chartcategory/as_cell/) | IChartDataCell nesnesini döndürür veya ayarlar.<br/>            Eğer kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır.<br/>            Okunabilir/Yazılabilir [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/tr/aspose.slides.charts/chartcategory/as_literal/) | AsLiteral nesnesini döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir **any**. |
| [`value`](/slides/python-net/tr/aspose.slides.charts/chartcategory/value/) | Eğer UseCell true ise bu özellik AsCell.Value property'yi temsil eder.<br/>            Eğer UseCell false ise bu özellik AsLiteral property'yi temsil eder.<br/>            Okunabilir/Yazılabilir **any**. |
| [`grouping_levels`](/slides/python-net/tr/aspose.slides.charts/chartcategory/grouping_levels/) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri.<br/>            Çok seviyeli kategori birden fazla gruplama seviyesi içerir.<br/>            Grublama seviyeleri indekslemesi sıfır tabanlıdır.<br/>            Yalnızca okunabilir [`IChartCategoryLevelsManager`](/slides/python-net/tr/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/tr/aspose.slides.charts/chartcategory/cached_value/) | Bir grafik kategorisinin önbelleğe alınmış değerini alır.<br/>            Yalnızca okunabilir [`ICachedChartValue`](/slides/python-net/tr/aspose.slides.charts/icachedchartvalue). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/chartcategory/remove/#) | Kategoriyi grafikten kaldırır. |

### Diğer Bağlantılar
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)