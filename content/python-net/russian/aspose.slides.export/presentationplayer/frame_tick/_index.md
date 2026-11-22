---
title: frame_tick event
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick событие
Событие frame_tick.
            
            Происходит, когда каждый кадр анимации, созданный [`PresentationAnimationsGenerator`](/slides/python-net/ru/aspose.slides.export/presentationanimationsgenerator), генерируется плеером.

### Определение:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/ru/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/ru/aspose.slides.export/frametickeventargs) |  |

### См. также
* класс [`FrameTickEventArgs`](/slides/python-net/ru/aspose.slides.export/frametickeventargs)
* класс [`PresentationAnimationsGenerator`](/slides/python-net/ru/aspose.slides.export/presentationanimationsgenerator)
* класс [`PresentationPlayer`](/slides/python-net/ru/aspose.slides.export/presentationplayer)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)