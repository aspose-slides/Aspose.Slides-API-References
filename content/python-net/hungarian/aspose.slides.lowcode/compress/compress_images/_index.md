---
title: compress_images method
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Csökkenti a képek felbontását a prezentációban, és törli a levágott területeket, hasonlóan a PowerPoint „Compress Pictures” funkciójához, amely minden képre alkalmazva van. A diákon, elrendezésdiókon és mesterdiákon lévő képek feldolgozásra kerülnek, beleértve a csoportos alakzatokban lévő képeket és az alakzatok képpel kitöltött részeit.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) | A feldolgozandó prezentáció. |
| resolution | [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression) | A cél felbontás a képek megjelenítési méretéhez viszonyítva.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/hu/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) változatlanul hagyja a képeket. |

### Megjegyzések

A már a cél felbontásnál vagy alatta lévő képek változatlanul maradnak; a képek soha nem lesznek felnagyítva.

Nem kerül feldolgozásra: dia hátterek, táblázatcellák kitöltései, diagramok, SmartArt, GIF képek (az animáció megőrzése érdekében), SVG és metafájl (EMF/WMF) képek.

A levágott területek véglegesen eltávolításra kerülnek, és a PowerPointban nem állíthatók vissza.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` **None** értékű. |

### Lásd még
* osztály [`Compress`](/slides/python-net/hu/aspose.slides.lowcode/compress)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* enumeráció [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression)
* modul [`aspose.slides.lowcode`](/slides/python-net/hu/aspose.slides.lowcode)
* könyvtár [`Aspose.Slides`](/slides/python-net)