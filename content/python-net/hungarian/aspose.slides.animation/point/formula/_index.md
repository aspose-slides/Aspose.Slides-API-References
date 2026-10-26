---
title: formula property
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozásán keresztül
description: 
type: docs
url: /hu/aspose.slides.animation/point/formula/
weight: 20
---
## formula tulajdonság
Formulák az értékekben, a from, to, by attribútumokban ezekből állhatnak:
            Standard aritmetikai operátorok: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Állandók: ‘pi’ ‘e’
            Feltételes operátorok: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Összehasonlító operátorok: '==', '>=', '', '!=', '!'
            Trigonometriai operátorok: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natív logaritmus ‘ln()’
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
* osztály [`Point`](/slides/python-net/hu/aspose.slides.animation/point)
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)