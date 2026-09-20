---
title: jpeg_quality property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality vlastnost
Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu.
            Čtení/Zápis **int**.


### Poznámky

Má vliv pouze tehdy, když dokument obsahuje JPEG obrázky.


Použijte tuto vlastnost k získání nebo nastavení kvality obrázků uvnitř dokumentu při ukládání do formátu PDF.
            Hodnota může být v rozmezí 0 až 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 znamená nejlepší kvalitu, ale minimální kompresi.


Výchozí hodnota je **95** .

### Definice:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Viz také
* třída [`HtmlOptions`](/slides/python-net/cs/aspose.slides.export/htmloptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)