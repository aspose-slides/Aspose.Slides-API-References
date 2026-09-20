---
title: get_font_bytes method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ifontsmanager/get_font_bytes/
weight: 30
---
## get_font_bytes(self, font_data, font_style) {#ifontdata-fontstyletype}
Hämtar bytearrayen som representerar teckensnittsdata för en angiven teckensnittsstil och teckensnittsdata.

### Returnerar

En bytearray som innehåller teckensnittsdata för den angivna teckensnittsstilen. Om teckensnittsdata eller stil inte hittas, returneras None.



```python
def get_font_bytes(self, font_data, font_style):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata) | Teckensnittsdatenobjektet som innehåller information om teckensnittet [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata). |
| font_style | [`FontStyleType`](/slides/python-net/sv/aspose.slides/fontstyletype) | Stilen för teckensnittet vars data ska hämtas [`FontStyleType`](/slides/python-net/sv/aspose.slides/fontstyletype). |



### Se även
* enumeration [`FontStyleType`](/slides/python-net/sv/aspose.slides/fontstyletype)
* class [`IFontData`](/slides/python-net/sv/aspose.slides/ifontdata)
* class [`IFontsManager`](/slides/python-net/sv/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)