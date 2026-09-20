---
title: jpeg_quality property
second_title: Aspose.Slides pro Python přes .NET API reference
description: 
type: docs
url: /cs/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality vlastnost
Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu.
            Čtení/Zápis **int**.


### Poznámky

Má účinek pouze, když dokument obsahuje JPEG obrázky.


Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF.
            Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 znamená nejlepší kvalitu, ale minimální kompresi.


Výchozí hodnota je **100** .

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
* třída [`PdfOptions`](/slides/python-net/cs/aspose.slides.export/pdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)