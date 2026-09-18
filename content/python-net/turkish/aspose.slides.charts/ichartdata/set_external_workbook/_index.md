---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| workbook_path | **str** | Hedef çalışma kitabının yolu |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Harici çalışma kitabı mevcut değil veya yüklenemiyor. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| workbook_path | **str** | Hedef çalışma kitabının yolu |
| update_chart_data | **bool** | Değer false ise yalnızca çalışma kitabı yolu güncellenir. <br/><br/>             Grafik verileri hedef çalışma kitabından yüklenmez ve güncellenmez. Hedef çalışma kitabı mevcut değilse veya erişilemezse kullanılabilir.<br/><br/>             Değer true ise grafik verileri hedef çalışma kitabından güncellenecektir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Harici çalışma kitabı mevcut değil veya yüklenemiyor. |

### Ayrıca Bakınız
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)