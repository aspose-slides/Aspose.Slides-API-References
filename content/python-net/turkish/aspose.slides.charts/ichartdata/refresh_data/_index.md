---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Kaynak çalışma kitabından yeniden yükleyerek grafik verilerini yeniler.


```python
def refresh_data(self):
    ...
```


### Açıklamalar

Eğer grafik harici bir çalışma kitabı kullanıyorsa, çalışma kitabının çağrı zamanında erişilebilir olması gerekir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Çalışma kitabı formatı desteklenmediğinde veya [`IChartData.data_source_type`](/slides/python-net/tr/aspose.slides.charts/ichartdata/data_source_type) olduğu<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/tr/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ve harici çalışma kitabına erişilemediğinde veya yüklenemediğinde fırlatılır. |



### Ayrıca Bakınız
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)