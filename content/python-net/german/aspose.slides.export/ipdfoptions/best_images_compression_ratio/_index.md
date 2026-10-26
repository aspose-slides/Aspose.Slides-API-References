---
title: best_images_compression_ratio property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio Eigenschaft
Zeigt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn auf **bool**.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und erfordert zusätzlichen RAM, und diese Option ist standardmäßig **bool**.false.


### Anmerkungen

Standard ist **bool**.false.

### Definition:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### Siehe auch
* Klasse [`IPdfOptions`](/slides/python-net/de/aspose.slides.export/ipdfoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)