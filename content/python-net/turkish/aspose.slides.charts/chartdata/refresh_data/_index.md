---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Kaynak çalışma kitabından yeniden yükleyerek grafik verilerini yeniler.

```python
def refresh_data(self):
    ...
```

### Açıklamalar

Eğer grafik harici bir çalışma kitabı kullanıyorsa, çalışma kitabının çağrı sırasında erişilebilir olması gerekir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Çalışma kitabı formatı desteklenmediğinde veya [`ChartData.data_source_type`](/slides/python-net/tr/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/tr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) olduğunda ve harici çalışma kitabına erişilemediğinde veya yüklenemediğinde fırlatılır. |

### Ayrıca Bakınız
* class [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)