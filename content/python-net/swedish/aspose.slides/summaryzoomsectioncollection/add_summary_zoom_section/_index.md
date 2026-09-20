---
title: add_summary_zoom_section method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
Skapar ett nytt Summary Zoom Section-objekt och lägger till det i samlingen

### Returnerar

Tillagt [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe) element



```python
def add_summary_zoom_section(self, section):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | Section för ett nytt Summary Zoom Section element [`ISection`](/slides/python-net/sv/aspose.slides/isection) |

### Anmärkningar

Om ett element för detta avsnitt redan finns i samlingen, returneras det befintliga elementet.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Det refererade avsnittet tillhör inte den aktuella presentationen eller innehåller inga bilder. |



### Se även
* klass [`ISection`](/slides/python-net/sv/aspose.slides/isection)
* klass [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe)
* klass [`ISummaryZoomSection`](/slides/python-net/sv/aspose.slides/isummaryzoomsection)
* klass [`SummaryZoomSectionCollection`](/slides/python-net/sv/aspose.slides/summaryzoomsectioncollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)