---
title: IDataLabelCollection class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection sınıfı

Bir serinin etiketlerini temsil eder.

The IDataLabelCollection tipi aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Koleksiyondaki tüm veri etiketlerinin varsayılan biçimini döndürür.<br/>            Yalnızca okunur [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Veri etiketlerinin lider çizgi biçimini temsil eder.<br/>            Yalnızca okunur [`IChartLinesFormat`](/slides/python-net/tr/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/is_visible/) | False, veri etiketi varsayılan olarak görünür değildir (ve bu yüzden DefaultDataLabelFormat özelliğinin tüm <br/>            Show*-bayrakları (ShowValue, ...) false olur).<br/>            Yalnızca okunur **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Koleksiyondaki görünür veri etiketlerinin sayısını alır.<br/>            Yalnızca okunur **int**. |
| [`count`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/count/) | Koleksiyondaki tüm veri etiketlerinin sayısını alır.<br/>            Yalnızca okunur **int**. |
| [`parent_series`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/parent_series/) | Üst grafik serisini döndürür.<br/>            Yalnızca okunur [`IChartSeries`](/slides/python-net/tr/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Veri etiketleri için varsayılan şekil türünü alır veya ayarlar.<br/>            Şekil tanımlı değilse [`ShapeType.NOT_DEFINED`](/slides/python-net/tr/aspose.slides/shapetype/NOT_DEFINED) döndürür. |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Belirtilen indekse sahip veri noktasının veri etiketini alır.

## Dizinleyici

| İsim | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`hide(self)`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/hide/#) | Tüm Show*-bayraklarını (ShowValue, ...) DefaultDataLabelFormat özelliğinde false olarak ayarlayarak veri etiketini varsayılan olarak gizli yapar.<br/>            Bu işlemden sonra IsVisible false olur. |
| [`index_of(self, value)`](/slides/python-net/tr/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Koleksiyondaki belirtilen DataLabel'ın indeksini döndürür. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)