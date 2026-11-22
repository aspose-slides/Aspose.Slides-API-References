---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Harici workbook'ı chart için veri kaynağı olarak ayarlar. Chart verileri hedef workbook'tan güncellenecektir.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| workbook_path | **str** | Hedef workbook'ın yolu |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Harici workbook mevcut değil veya yüklenemiyor. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Harici workbook'ı chart için veri kaynağı olarak ayarlar.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| workbook_path | **str** | Hedef workbook'ın yolu |
| update_chart_data | **bool** | Değer false ise yalnızca workbook yolu güncellenecektir. <br/><br/>             Chart verileri hedef workbook'tan yüklenmeyecek ve güncellenmeyecek. Hedef workbook mevcut olmadığında veya erişilemez olduğunda kullanılabilir.<br/><br/>             Değer true ise chart verileri hedef workbook'tan güncellenecektir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Harici workbook mevcut değil veya yüklenemiyor. |



### Ayrıca Bakınız
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)