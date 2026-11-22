---
title: frame_tick event
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick evento
Evento frame tick.

Si verifica quando ogni fotogramma dell'animazione creato da [`PresentationAnimationsGenerator`](/slides/python-net/it/aspose.slides.export/presentationanimationsgenerator) viene generato dal lettore.

### Definizione:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/it/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/it/aspose.slides.export/frametickeventargs) |  |

### Vedi anche
* classe [`FrameTickEventArgs`](/slides/python-net/it/aspose.slides.export/frametickeventargs)
* classe [`PresentationAnimationsGenerator`](/slides/python-net/it/aspose.slides.export/presentationanimationsgenerator)
* classe [`PresentationPlayer`](/slides/python-net/it/aspose.slides.export/presentationplayer)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)