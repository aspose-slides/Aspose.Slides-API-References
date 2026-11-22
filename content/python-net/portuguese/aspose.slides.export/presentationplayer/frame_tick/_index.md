---
title: frame_tick event
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## evento frame_tick
Evento frame_tick.

Ocorre quando cada quadro da animação criada por [`PresentationAnimationsGenerator`](/slides/python-net/pt/aspose.slides.export/presentationanimationsgenerator) é gerado pelo reprodutor.

### Definição:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/pt/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/pt/aspose.slides.export/frametickeventargs) |  |

### Veja Também
* classe [`FrameTickEventArgs`](/slides/python-net/pt/aspose.slides.export/frametickeventargs)
* classe [`PresentationAnimationsGenerator`](/slides/python-net/pt/aspose.slides.export/presentationanimationsgenerator)
* classe [`PresentationPlayer`](/slides/python-net/pt/aspose.slides.export/presentationplayer)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)