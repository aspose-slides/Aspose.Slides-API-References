---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Harita için dış çalışma kitabını veri kaynağı olarak ayarlar. Harita verileri hedef çalışma kitabından güncellenecektir.


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
| **RuntimeError(Proxy error(InvalidOperationException))** | Dış çalışma kitabı mevcut değil veya yüklenemiyor. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Harita için dış çalışma kitabını veri kaynağı olarak ayarlar.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| workbook_path | **str** | Hedef çalışma kitabının yolu |
| update_chart_data | **bool** | Eğer değer false ise yalnızca çalışma kitabı yolu güncellenecektir. <br/><br/>             Harita verileri hedef çalışma kitabından yüklenmez ve güncellenmez. Hedef çalışma kitabı mevcut değilse veya erişilemezse kullanılabilir.<br/><br/>             Eğer değer true ise harita verileri hedef çalışma kitabından güncellenecektir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dış çalışma kitabı mevcut değil veya yüklenemiyor. |



### Diğer Bilgiler
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)