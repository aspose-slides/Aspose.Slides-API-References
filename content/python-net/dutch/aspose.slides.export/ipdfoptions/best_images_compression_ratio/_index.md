---
title: best_images_compression_ratio property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio eigenschap
Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd.  
Als deze is ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document.  
Het selecteren van de beste beeldcompressieverhouding is computationeel intensief en vereist extra RAM, en deze optie is standaard **bool**.false.


### Opmerkingen

Standaard is **bool**.false.

### Definitie:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### Zie ook
* klasse [`IPdfOptions`](/slides/python-net/nl/aspose.slides.export/ipdfoptions)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)