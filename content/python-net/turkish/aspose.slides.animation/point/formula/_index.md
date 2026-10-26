---
title: formula property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/point/formula/
weight: 20
---
## formül özelliği
Değerlerde, from, to, by özniteliklerinde kullanılan formüller şunlardan oluşabilir:
            Standart aritmetik operatörler: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Sabitler: ‘pi’ ‘e’
            Koşul operatörleri: ‘abs’, ‘min’, ‘max’, ‘?’ (eğer)
            Karşılaştırma operatörleri: '==', '>=', '', '!=', '!'
            Trigonometrik operatörler: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Doğal logaritma ‘ln()’
            Özellik referansları (host destekli özellikler)
            
            örnek: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Okunur/yazılır **str**.

### Tanım:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Ayrıca
* sınıf [`Point`](/slides/python-net/tr/aspose.slides.animation/point)
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)