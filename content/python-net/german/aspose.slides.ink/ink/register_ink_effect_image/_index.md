---
title: register_ink_effect_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Registriert ein Bild in die Sammlung benutzerdefinierter Bilder, die zur Simulation visueller Effekte für Ink-Pinsel verwendet werden.
Diese Bilder werden beim Rendern von Ink mit bestimmten [`InkEffectType`](/slides/python-net/de/aspose.slides.ink/inkeffecttype)-Werten verwendet,
wie z. B. Galaxy, Rainbow usw. Durch das Bereitstellen eigener Bilder können Sie steuern, wie jeder Ink-Effekt aussieht.

```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/de/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/de/aspose.slides/iimage) |  |

### Anmerkungen

Diese Methode ermöglicht es, die Standard-Ink-Effekt-Texturen durch benutzerdefinierte zu ersetzen,
was besonders nützlich ist, wenn Standard-Assets durch Lizenzierung eingeschränkt oder zur Laufzeit nicht verfügbar sind.
Jedes registrierte Werte-Paar muss einen [`InkEffectType`](/slides/python-net/de/aspose.slides.ink/inkeffecttype)-Wert mit einem entsprechenden
[`IImage`](/slides/python-net/de/aspose.slides/iimage)-Objekt (z. B. Bitmap oder einer Aspose-Bild-Schnittstelle) verknüpfen.

### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`Ink`](/slides/python-net/de/aspose.slides.ink/ink)
* Aufzählung [`InkEffectType`](/slides/python-net/de/aspose.slides.ink/inkeffecttype)
* Modul [`aspose.slides.ink`](/slides/python-net/de/aspose.slides.ink)
* Bibliothek [`Aspose.Slides`](/slides/python-net)