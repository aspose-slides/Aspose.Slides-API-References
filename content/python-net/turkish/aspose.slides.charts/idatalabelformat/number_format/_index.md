---
title: number_format property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format özelliği
DataLabels nesnesi için biçim dizesini temsil eder.
            Okunur/Yazılır **str**.

### Açıklamalar

Eğer bu DataLabelFormat nesnesinin üst nesnesi bir DataLabelCollection veri etiketi koleksiyonu ise, bu özellik yeni veri etiketleri için DataLabelCollection koleksiyonundaki NumberFormat özelliğinin varsayılan değerini alır veya ayarlar. 
Bu özellik bir değerle ayarlandığında, bu değer DataLabelCollection koleksiyonundaki tüm veri etiketleri için NumberFormat özelliğine de uygulanır (ör. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" tüm DataLabels[i].NumberFormat değerini val yapar).

### Tanım:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Ayrıca Bakınız
* sınıf [`IDataLabelFormat`](/slides/python-net/tr/aspose.slides.charts/idatalabelformat)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)