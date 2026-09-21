---
title: compress_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

### Retourwaarde

Een **bool** die aangeeft of de afbeelding succesvol is gecomprimeerd. Retourneert **True** als de afbeelding is verkleind of bijgesneden, anders **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Als true, verwijdert de methode de bijgesneden gebieden van de afbeelding, waardoor de grootte mogelijk nog verder wordt verkleind. |
| resolution | [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression) | De doelresolutie voor compressie, gespecificeerd als een waarde van de [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression) enum. |

### Opmerkingen

Deze methode verandert de grootte en resolutie van de afbeelding, vergelijkbaar met de functie "Picture Format -> Compress Pictures" van PowerPoint.

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de resolutie geen geldige waarde is. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

### Retourwaarde

Een **bool** die aangeeft of de afbeelding succesvol is gecomprimeerd. Retourneert **True** als de afbeelding is verkleind of bijgesneden, anders **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Als true, verwijdert de methode de bijgesneden gebieden van de afbeelding, waardoor de grootte mogelijk nog verder wordt verkleind. |
| resolution | **float** | De doelresolutie in DPI. Deze waarde moet positief zijn en bepaalt hoe de afbeelding wordt verkleind. |

### Opmerkingen

Deze methode verandert de grootte en resolutie van de afbeelding, vergelijkbaar met de functie "Picture Format -> Compress Pictures" van PowerPoint.

### Uitzonderingen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de resolutie geen positieve waarde is. |



### Zie ook
* klasse [`IPictureFillFormat`](/slides/python-net/nl/aspose.slides/ipicturefillformat)
* enumeratie [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)