---
title: add_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Voegt een kopie van een afbeelding toe van een andere presentatie.

### Retour

Afbeelding toegevoegd.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | Bronafbeelding. |


## add_image(self, image) {#iimage}
Voegt een afbeelding toe aan een presentatie.

### Retour

Afbeelding toegevoegd.



```python
def add_image(self, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/nl/aspose.slides/iimage) | Afbeelding om toe te voegen. |

### Opmerkingen

Deze methode converteert WMF/EMF-metabestanden naar raster-PNG-afbeeldingen voordat ze in een presentatie worden ingevoegd.


## add_image(self, stream) {#iorawiobase}
Voegt een afbeelding toe aan een presentatie vanaf een stream.

### Retour

Afbeelding toegevoegd.



```python
def add_image(self, stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om afbeelding uit toe te voegen. |

### Opmerkingen

Deze methode kan WMF/EMF-metabestanden toevoegen aan een presentatie zonder ze te converteren naar raster-PNG-afbeeldingen.


## add_image(self, buffer) {#bytes}
Voegt een afbeelding toe aan een presentatie vanuit een gespecificeerde buffer.

### Retour

Afbeelding toegevoegd.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
Voegt een afbeelding toe aan een presentatie vanuit een Svg-object.

### Retour

Afbeelding toegevoegd.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage) | Svg-afbeeldingsobject [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage) |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wanneer de svgImage-parameter None is. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Creëert en voegt een afbeelding toe aan een presentatie vanaf een stream.

### Retour

Toegevoegd [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om afbeeldingsbestand uit toe te voegen. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior) | Het gedrag dat op de stream zal worden toegepast. |



### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* klasse [`ImageCollection`](/slides/python-net/nl/aspose.slides/imagecollection)
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage)
* enumeratie [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)