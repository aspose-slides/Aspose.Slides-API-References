---
title: formula property
second_title: Aspose.Slides için Python .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formül özelliği
Değerler, from, to, by öznitelikleri içindeki formüller şunlardan oluşabilir:
            Standart aritmetik operatörler: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Sabitler: ‘pi’ ‘e’
            Koşullu operatörler: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Karşılaştırma operatörleri: '==', '>=', '', '!=', '!'
            Trigonometri operatörleri: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Doğal logaritma ‘ln()’
            Özellik referansları (host desteklenen özellikler)
            
            örnek: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Okunabilir/Yazılabilir **str**.

### Tanım:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### İlgili
* sınıf [`IPoint`](/slides/python-net/tr/aspose.slides.animation/ipoint)
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)