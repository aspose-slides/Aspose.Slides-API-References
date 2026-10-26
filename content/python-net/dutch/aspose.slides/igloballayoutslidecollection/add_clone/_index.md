---
title: add_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

### Retourwaarde

Toegevoegde dia.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Dia om te klonen. |

### Opmerkingen

Bij het klonen van een lay-out tussen verschillende presentaties kan de master van de lay-out ook worden gekloond om de bronopmaak te behouden. Een interne register wordt gebruikt om automatisch gekloonde masters bij te houden om het maken van meerdere kloons van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd.



## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

### Retourwaarde

Toegevoegde dia.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Dia om te klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide) | Masterdia voor een nieuwe lay-out. |

### Opmerkingen

Nieuwe lay-out wordt gekoppeld aan de gedefinieerde master in de bestemmingspresentatie. Dit is dus analoog aan kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.



### Zie ook
* klasse [`IGlobalLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/igloballayoutslidecollection)
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)