---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Eğer kategori koleksiyon içinde mevcutsa, onu döndür. Aksi takdirde, yeni bir grafik kategorisi oluşturur 
            [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) ve koleksiyona ekler.

### Döndürür

Eklenmiş veya mevcut kategori.



```python
def add(self, chart_data_cell):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) | Grafik kategorisi oluşturmak için kullanılan hücre. |


## add(self, value) {#any}
Değerden yeni [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory) oluşturur ve koleksiyona ekler.

### Döndürür

Eklenmiş [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | **any** | Değer. |

### Açıklamalar

Bu metod, AUTO_DATA adında bir çalışma sayfası ekler ve tüm değerleri oraya ekler.  Eğer [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook)'yi hücre değerlerini eklemek veya düzenlemek için kullanıyorsanız, bu çalışma sayfasını kullanmadığınızdan emin olun
            Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i geçmemelidir

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | limit aşılırsa |



### Diğer
* sınıf [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory)
* sınıf [`IChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcategorycollection)
* sınıf [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)
* sınıf [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)