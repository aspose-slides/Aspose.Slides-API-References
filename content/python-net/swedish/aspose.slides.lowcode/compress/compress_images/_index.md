---
title: compress_images method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Minskar upplösningen på bilder i presentationen och tar bort deras beskärda områden,
            liknande PowerPoints "Compress Pictures" som tillämpas på alla bilder.
            Bilder på bildspel, layoutbilder och masternbilder bearbetas, inklusive bilder i gruppformer
            och bildfyllningar av former.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation) | Presentationen att bearbeta. |
| resolution | [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression) | Måluplösning relativt den storlek som varje bild visas i.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/sv/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) lämnar bilder oförändrade. |

### Anmärkningar

Bilder som redan är på eller under målupplösningen lämnas oförändrade; bilder skalas aldrig upp.

Ej bearbetade: bildbakgrunder, tabellcellfyllningar, diagram, SmartArt, GIF-bilder (för att bevara animation),
            SVG- och metafilbilder (EMF/WMF).

Beskärda områden tas bort permanent och kan inte återställas i PowerPoint.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` är `None`. |



### Se även
* klass [`Compress`](/slides/python-net/sv/aspose.slides.lowcode/compress)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* enumeration [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* bibliotek [`Aspose.Slides`](/slides/python-net)