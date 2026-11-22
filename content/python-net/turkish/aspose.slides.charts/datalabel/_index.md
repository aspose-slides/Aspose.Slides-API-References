---
title: DataLabel class
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/datalabel/
---
## DataLabel sınıfı

Bir serinin etiketlerini temsil eder.

DataLabel tipi aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/tr/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | DataLabel sınıfının yeni bir örneğini oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/datalabel/chart/) | Üst grafik döndürür.<br/>            Yalnızca-okunur [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/tr/aspose.slides.charts/datalabel/is_visible/) | False, veri etiketinin görünür olmadığı anlamına gelir (ve bu yüzden tüm Show*-bayrakları (ShowValue, ...) false olur).<br/>            Yalnızca-okunur **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/tr/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Zengin biçimlendirilmiş metin içerebilir. Bu özellik None değilse, bu <br/>            biçimlendirilmiş metin değeri veri etiketinin otomatik oluşturulan metninin üzerine yazar.<br/>            Veri etiketinin otomatik oluşturulan metni, ShowSeriesName, <br/>            ShowValue, ... özellikleriyle yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilmiş metni ifade eder.<br/>            Yalnızca-okunur [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/tr/aspose.slides.charts/datalabel/text_format/) | Metin biçimini döndürür.<br/>            Yalnızca-okunur [`IChartTextFormat`](/slides/python-net/tr/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/tr/aspose.slides.charts/datalabel/x/) | Başlığın x koordinatını, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.charts/datalabel/y/) | Başlığın y koordinatını, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.charts/datalabel/width/) | Başlığın genişliğini, grafiğin genişliğinin bir kesri olarak döndürür veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.charts/datalabel/height/) | Başlığın yüksekliğini, grafiğin yüksekliğinin bir kesri olarak döndürür veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`right`](/slides/python-net/tr/aspose.slides.charts/datalabel/right/) | Sağ.<br/>            Yalnızca-okunur **float**. |
| [`bottom`](/slides/python-net/tr/aspose.slides.charts/datalabel/bottom/) | Alt.<br/>            Yalnızca-okunur **float**. |
| [`data_label_format`](/slides/python-net/tr/aspose.slides.charts/datalabel/data_label_format/) | Veri etiketi biçimini döndürür.<br/>            Yalnızca-okunur [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/tr/aspose.slides.charts/datalabel/value_from_cell/) | Çalışma kitabı veri hücresini alır veya ayarlar. IDataLabelFormat.ShowLabelValueFromCell özelliği true ise uygulanır. |
| [`label_shape_type`](/slides/python-net/tr/aspose.slides.charts/datalabel/label_shape_type/) | Veri etiketinin şekil tipini alır veya ayarlar.<br/>             Şekil tanımlı değilse [`ShapeType.NOT_DEFINED`](/slides/python-net/tr/aspose.slides/shapetype/NOT_DEFINED) döndürür. |
| [`actual_x`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_x/) | Grafik öğesinin gerçek x konumunu (sol) grafiğin sol üst köşesine göre belirtir.<br/>            Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın.<br/>            Okunur **float**. |
| [`actual_y`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_y/) | Grafik öğesinin gerçek üst konumunu grafiğin sol üst köşesine göre belirtir.<br/>            Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın.<br/>            Okunur **float**. |
| [`actual_width`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_width/) | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın.<br/>            Okunur **float**. |
| [`actual_height`](/slides/python-net/tr/aspose.slides.charts/datalabel/actual_height/) | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın.<br/>            Okunur **float**. |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/datalabel/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`hide(self)`](/slides/python-net/tr/aspose.slides.charts/datalabel/hide/#) | Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizli yapar.<br/>            Bu işlemden sonra IsVisible false olacaktır. |
| [`get_actual_label_text(self)`](/slides/python-net/tr/aspose.slides.charts/datalabel/get_actual_label_text/#) | DataLabelFormat ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/tr/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | TextFrameForOverriding'i parametre "text" içindeki metinle başlatır.<br/>            TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir. |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)