---
title: compress_image method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

### Retour

Een **bool** die aangeeft of de afbeelding succesvol is gecomprimeerd. Retourneert **True** als de afbeelding is verkleind of bijgesneden, anders **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Als true, zal de methode de bijgesneden gebieden van de afbeelding verwijderen, waardoor de grootte mogelijk nog verder wordt verkleind. |
| resolution | [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression) | De doelresolutie voor compressie, gespecificeerd als een waarde van de enum [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression). |

### Opmerkingen

Deze methode wijzigt de grootte en resolutie van de afbeelding, vergelijkbaar met de functie "Picture Format -> Compress Pictures" van PowerPoint.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de resolutie geen geldige waarde is. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

### Retour

Een **bool** die aangeeft of de afbeelding succesvol is gecomprimeerd. Retourneert **True** als de afbeelding is verkleind of bijgesneden, anders **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Als true, zal de methode de bijgesneden gebieden van de afbeelding verwijderen, waardoor de grootte mogelijk nog verder wordt verkleind. |
| resolution | **float** | De doelresolutie in DPI. Deze waarde moet positief zijn en bepaalt hoe de afbeelding wordt verkleind. |

### Opmerkingen

Deze methode wijzigt de grootte en resolutie van de afbeelding, vergelijkbaar met de functie "Picture Format -> Compress Pictures" van PowerPoint.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de resolutie geen positieve waarde is. |



### Zie ook
* klasse [`PictureFillFormat`](/slides/python-net/nl/aspose.slides/picturefillformat)
* enumeratie [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)