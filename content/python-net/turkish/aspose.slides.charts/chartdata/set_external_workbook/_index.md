---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Grafik için veri kaynağı olarak harici çalışma kitabını ayarlar. Grafik verileri hedef çalışma kitabından güncellenecektir.


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
Grafik için veri kaynağı olarak harici çalışma kitabını ayarlar.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| workbook_path | **str** | Hedef çalışma kitabının yolu |
| update_chart_data | **bool** | Değer false ise yalnızca çalışma kitabı yolu güncellenecektir.<br/><br/>Grafik verileri hedef çalışma kitabından yüklenmeyecek ve güncellenmeyecek. Hedef çalışma kitabı mevcut olmadığında veya erişilemediğinde kullanılabilir.<br/><br/>Değer true ise grafik verileri hedef çalışma kitabından güncellenecektir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Harici çalışma kitabı mevcut değil veya yüklenemiyor. |



### İlgili
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)