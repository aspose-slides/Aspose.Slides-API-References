---
title: formula property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.animation/ipoint/formula/
weight: 10
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
            
            misalnya: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
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
* kelas [`IPoint`](/slides/python-net/id/aspose.slides.animation/ipoint)
* modul [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* perpustakaan [`Aspose.Slides`](/slides/python-net)