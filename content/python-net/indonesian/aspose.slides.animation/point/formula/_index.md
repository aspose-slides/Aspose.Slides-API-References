---
title: formula property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.animation/point/formula/
weight: 20
---
## properti formula
Formula dalam nilai, atribut from, to, by dapat terdiri dari:
            Operator aritmetika standar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Konstanta: ‘pi’ ‘e’
            Operator bersyarat: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Operator perbandingan: '==', '>=', '', '!=', '!'
            Operator trigonometri: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logaritma natural ‘ln()’
            Referensi properti (properti yang didukung host)
            
            contoh: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Baca/tulis **str**.

### Definisi:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### Lihat Juga
* kelas [`Point`](/slides/python-net/id/aspose.slides.animation/point)
* modul [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* pustaka [`Aspose.Slides`](/slides/python-net)