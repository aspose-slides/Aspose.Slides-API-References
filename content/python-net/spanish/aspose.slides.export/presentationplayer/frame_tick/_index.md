---
title: frame_tick event
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## evento frame_tick
Evento de tick de fotograma.
            
            Ocurre cuando cada fotograma de la animación creada por [`PresentationAnimationsGenerator`](/slides/python-net/es/aspose.slides.export/presentationanimationsgenerator) es generado por el reproductor.

### Definición:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/es/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/es/aspose.slides.export/frametickeventargs) |  |


### Ver también
* clase [`FrameTickEventArgs`](/slides/python-net/es/aspose.slides.export/frametickeventargs)
* clase [`PresentationAnimationsGenerator`](/slides/python-net/es/aspose.slides.export/presentationanimationsgenerator)
* clase [`PresentationPlayer`](/slides/python-net/es/aspose.slides.export/presentationplayer)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)