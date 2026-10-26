---
title: register_ink_effect_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Registreert een afbeelding in de collectie van aangepaste afbeeldingen die worden gebruikt om visuele effecten voor inktpennen te simuleren.
            Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke [`InkEffectType`](/slides/python-net/nl/aspose.slides.ink/inkeffecttype) waarden,
            zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te leveren, kunt u bepalen hoe elk inkt effect verschijnt.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/nl/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/nl/aspose.slides/iimage) |  |

### Opmerkingen

Deze methode staat toe de standaard inkt effect texturen te vervangen door door de gebruiker gedefinieerde,
            wat bijzonder nuttig is wanneer standaard assets beperkt zijn door licenties of niet beschikbaar zijn tijdens uitvoering.
            Elk geregistreerd waardepaar moet een [`InkEffectType`](/slides/python-net/nl/aspose.slides.ink/inkeffecttype) waarde koppelen aan een overeenkomstig
            [`IImage`](/slides/python-net/nl/aspose.slides/iimage) object (bijv. Bitmap, of een Aspose afbeelding interface).

### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* klasse [`Ink`](/slides/python-net/nl/aspose.slides.ink/ink)
* enumeratie [`InkEffectType`](/slides/python-net/nl/aspose.slides.ink/inkeffecttype)
* module [`aspose.slides.ink`](/slides/python-net/nl/aspose.slides.ink)
* bibliotheek [`Aspose.Slides`](/slides/python-net)