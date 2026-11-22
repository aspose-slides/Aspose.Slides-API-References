---
title: frame_tick event
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick olayı
Frame tick olayı.

[`PresentationAnimationsGenerator`](/slides/python-net/tr/aspose.slides.export/presentationanimationsgenerator) tarafından oluşturulan animasyonun her bir çerçevesi oynatıcı tarafından üretildiğinde gerçekleşir.

### Tanım:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/tr/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/tr/aspose.slides.export/frametickeventargs) |  |


### İlgili
* sınıf [`FrameTickEventArgs`](/slides/python-net/tr/aspose.slides.export/frametickeventargs)
* sınıf [`PresentationAnimationsGenerator`](/slides/python-net/tr/aspose.slides.export/presentationanimationsgenerator)
* sınıf [`PresentationPlayer`](/slides/python-net/tr/aspose.slides.export/presentationplayer)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)