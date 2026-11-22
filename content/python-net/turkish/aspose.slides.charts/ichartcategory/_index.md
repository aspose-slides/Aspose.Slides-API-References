---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartcategory/
---
## IChartCategory sınıfı

Grafik kategorilerini temsil eder.

IChartCategory türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`use_cell`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/use_cell/) | Eğer true ise AsCell özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori <br/>            depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir).<br/>            Eğer false ise AsLiteral özelliği geçerlidir. Başka bir deyişle, çalışma sayfası <br/>            depolamak için kullanılmaz (ve bu durumda çok seviyeli kategoriler desteklenmez).<br/>            Yalnızca okunur **bool**. |
| [`as_cell`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/as_cell/) | IChartDataCell nesnesini döndürür veya ayarlar.<br/>            Kategori çok seviyeli ise, seviye "0" için IChartDataCell nesnesi kullanılır.<br/>            Okuma/yazma [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/as_literal/) | UseCell false ise AsLiteral'ı döndürür veya ayarlar.<br/>            Okuma/yazma **any**. |
| [`value`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/value/) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder.<br/>            UseCell false ise bu özellik AsLiteral özelliğini temsil eder.<br/>            Okuma/yazma **any**. |
| [`cached_value`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/cached_value/) | Bir grafik kategorisinin önbelleğe alınmış değerini alır.<br/>            Yalnızca okunur [`ICachedChartValue`](/slides/python-net/tr/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/grouping_levels/) | Grafik kategorisi gruplama seviyelerinin değerlerinin yönetilen konteyneri.<br/>            Çok seviyeli kategori birden fazla gruplama seviyesi içerir.<br/>            Gruplama seviyesi indekslemesi sıfır tabanlıdır.<br/>            Yalnızca okunur [`IChartCategoryLevelsManager`](/slides/python-net/tr/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`remove(self)`](/slides/python-net/tr/aspose.slides.charts/ichartcategory/remove/#) | Kategoriyi grafikten kaldırır. |


### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)