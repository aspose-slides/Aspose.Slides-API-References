---
title: add_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Voeg een afbeelding toe aan een presentatie.

### Returns

Afbeelding toegevoegd.



```python
def add_image(self, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/nl/aspose.slides/iimage) | Afbeelding om toe te voegen. |

### Remarks

Deze methode converteert WMF/EMF-metabestanden naar raster-PNG-afbeeldingen voordat ze in een presentatie worden ingevoegd.


## add_image(self, stream) {#iorawiobase}
Voeg een afbeelding toe aan een presentatie vanuit een stream.

### Returns

Afbeelding toegevoegd.



```python
def add_image(self, stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om afbeelding van toe te voegen. |

### Remarks

Deze methode kan WMF/EMF-metabestanden aan een presentatie toevoegen zonder ze naar raster-PNG-afbeeldingen te converteren.


## add_image(self, buffer) {#bytes}
Voegt een afbeelding toe aan een presentatie vanuit een opgegeven buffer.

### Returns

Afbeelding toegevoegd.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, image_source) {#ippimage}
Voegt een kopie van een afbeelding toe vanuit een andere presentatie.

### Returns

Afbeelding toegevoegd.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | Bronafbeelding. |


## add_image(self, svg_image) {#isvgimage}
Voeg een afbeelding toe aan een presentatie vanuit een SVG-object.

### Returns

Afbeelding toegevoegd.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage) | SVG-afbeeldingsobject [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage) |

### Exceptions

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt gegooid wanneer de svgImage-parameter None is. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Maakt een afbeelding en voegt deze toe aan een presentatie vanuit een stream.

### Returns

Toegevoegde [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om afbeeldingbestand van toe te voegen. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior) | Het gedrag dat op de stream wordt toegepast. |



### See Also
* class [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/nl/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)