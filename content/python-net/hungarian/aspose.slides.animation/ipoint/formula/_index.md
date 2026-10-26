---
title: formula property
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formula tulajdonság
A képletek az értékek, a from, to, by attribútumokban a következőkből állhatnak:
            Szabványos aritmetikai operátorok: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Konstansok: ‘pi’ ‘e’
            Feltételes operátorok: ‘abs’, ‘min’, ‘max’, ‘?’ (ha)
            Összehasonlító operátorok: '==', '>=', '', '!=', '!'
            Trigonometrikus operátorok: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Természetes logaritmus ‘ln()’
            Tulajdonság hivatkozások (host által támogatott tulajdonságok)
            
            például: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Olvasás/írás **str**.

### Definíció:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Lásd még
* osztály [`IPoint`](/slides/python-net/hu/aspose.slides.animation/ipoint)
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)