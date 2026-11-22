---
title: frame_tick event
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick événement
Événement frame_tick.

Se produit lorsque chaque image de l'animation créée par [`PresentationAnimationsGenerator`](/slides/python-net/fr/aspose.slides.export/presentationanimationsgenerator) est générée par le lecteur.

### Définition:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| Paramètre | Type | Description |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/fr/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/fr/aspose.slides.export/frametickeventargs) |  |

### Voir aussi
* classe [`FrameTickEventArgs`](/slides/python-net/fr/aspose.slides.export/frametickeventargs)
* classe [`PresentationAnimationsGenerator`](/slides/python-net/fr/aspose.slides.export/presentationanimationsgenerator)
* classe [`PresentationPlayer`](/slides/python-net/fr/aspose.slides.export/presentationplayer)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)