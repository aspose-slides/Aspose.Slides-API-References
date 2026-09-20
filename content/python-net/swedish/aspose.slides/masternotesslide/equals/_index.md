---
title: equals method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Bestämmer om de två IBaseSlide-instanserna är lika.
Returnerat värde beräknas baserat på bildens struktur och statiska innehåll.
Två bilder är lika om alla former, stilar, texter, animation och andra inställningar etc. är lika.
Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder.

### Returnerar

**true** om den angivna IBaseSlide är lika med den aktuella IBaseSlide; annars, **false**.

```python
def equals(self, slide):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide) | IBaseSlide att jämföra med den aktuella IBaseSlide. |

### Se även
* klass [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide)
* klass [`MasterNotesSlide`](/slides/python-net/sv/aspose.slides/masternotesslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)