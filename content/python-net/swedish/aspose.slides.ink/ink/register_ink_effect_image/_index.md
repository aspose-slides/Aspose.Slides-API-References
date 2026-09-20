---
title: register_ink_effect_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Registrerar en bild till samlingen av anpassade bilder som används för att simulera visuella effekter för bläckpenslar.
            Dessa bilder används vid rendering av bläck med specifika [`InkEffectType`](/slides/python-net/sv/aspose.slides.ink/inkeffecttype)-värden,
            såsom Galaxy, Rainbow osv. Genom att tillhandahålla egna bilder kan du kontrollera hur varje bläckeffekt visas.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/sv/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/sv/aspose.slides/iimage) |  |

### Anmärkningar

Denna metod möjliggör att ersätta standardtexturerna för bläckeffekter med användardefinierade,
            vilket är särskilt användbart när standardtillgångar är begränsade av licensiering eller inte är tillgängliga vid körning.
            Varje registrerat värdepar måste associera ett [`InkEffectType`](/slides/python-net/sv/aspose.slides.ink/inkeffecttype)-värde med ett motsvarande
            [`IImage`](/slides/python-net/sv/aspose.slides/iimage)-objekt (t.ex. Bitmap, eller ett Aspose-bildgränssnitt).



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`Ink`](/slides/python-net/sv/aspose.slides.ink/ink)
* enumeration [`InkEffectType`](/slides/python-net/sv/aspose.slides.ink/inkeffecttype)
* modul [`aspose.slides.ink`](/slides/python-net/sv/aspose.slides.ink)
* bibliotek [`Aspose.Slides`](/slides/python-net)