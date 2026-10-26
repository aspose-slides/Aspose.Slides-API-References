---
title: get_font_bytes method
second_title: Aspose.Slides Python számára a .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/ifontsmanager/get_font_bytes/
weight: 30
---
## get_font_bytes(self, font_data, font_style) {#ifontdata-fontstyletype}
Visszaadja a megadott betűstílushoz és betűadatokhoz tartozó betűadatokat tartalmazó bájt tömböt.

### Returns
Egy bájt tömb, amely a megadott betűstílushoz tartozó betűadatokat tartalmazza. Ha a betűadat vagy a stílus nem található, None értéket ad vissza.

```python
def get_font_bytes(self, font_data, font_style):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata) | A betűadat objektum, amely a [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata) betűvel kapcsolatos információkat tartalmazza. |
| font_style | [`FontStyleType`](/slides/python-net/hu/aspose.slides/fontstyletype) | A betű stílusa, amelyhez a betűadatokat le kell kérni [`FontStyleType`](/slides/python-net/hu/aspose.slides/fontstyletype). |

### See Also
* felsorolás [`FontStyleType`](/slides/python-net/hu/aspose.slides/fontstyletype)
* osztály [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata)
* osztály [`IFontsManager`](/slides/python-net/hu/aspose.slides/ifontsmanager)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)