---
title: jpeg_quality property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality vlastnost
Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu.
            Čtení/zápis **int**.


### Poznámky

Má efekt pouze pokud dokument obsahuje JPEG obrázky.


Použijte tuto vlastnost k získání nebo nastavení kvality obrázků uvnitř dokumentu při ukládání do PDF formátu.
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
* třída [`IPdfOptions`](/slides/python-net/cs/aspose.slides.export/ipdfoptions)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)