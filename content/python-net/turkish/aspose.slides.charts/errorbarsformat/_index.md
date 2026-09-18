---
title: ErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat sınıfı

Grafik serisinin hata çubuklarını temsil eder. ErrorBars özel değerleri IChartDataPointCollection içinde bulunur ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) özelliğinde).

ErrorBarsFormat tipi aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`type`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/type/) | Hata çubuklarının türünü alır veya ayarlar. <br/>            Read/write [`ErrorBarType`](/slides/python-net/tr/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/value_type/) | Hata çubuklarının uzunluğunu belirlemenin olası yollarını temsil eder. <br/>            Özel değer türü durumunda, değeri belirtmek için serinin DataPoints koleksiyonundaki belirli veri noktasının [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) özelliğini kullanın.<br/>            Fixed, Percentage veya StandardDeviation değer türü durumunda, değeri belirtmek için Value özelliğini kullanın.  <br/>            Read/write [`ErrorBarValueType`](/slides/python-net/tr/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/has_end_cap/) | Hata çubuklarının uç kapağı çizilmediğini belirtir.<br/>            Read/write **bool**. |
| [`value`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/value/) | Hata çubuklarının uzunluğunu belirlemek için Fixed, Percentage ve StandardDeviation değer türleriyle kullanılan değeri alır veya ayarlar. <br/>            Diğer tüm durumlarda NaN döndürür.<br/>            Read/write **float**. |
| [`format`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/format/) | Hata çubuklarının biçimini temsil eder.<br/>            Read/write [`IFormat`](/slides/python-net/tr/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/chart/) | Üst grafik nesnesini döndürür.<br/>            Read-only [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/is_visible/) | Error Bars görünürlüğünü alır veya ayarlar.<br/>            Read/write **bool**. |
| [`slide`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Ayrıca Bakınız
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)