---
title: compress_images method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Snižuje rozlišení obrázků v prezentaci a odstraňuje jejich oříznuté oblasti, podobně jako funkce „Compress Pictures“ v PowerPointu použita na všechny obrázky. Obrázky na snímcích, rozvrhových snímcích a hlavních snímcích jsou zpracovány, včetně obrázků uvnitř seskupených tvarů a výplní obrázků tvarů.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) | Prezentace, která se má zpracovat. |
| resolution | [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression) | Cílové rozlišení relativně k velikosti, v níž je každý obrázek zobrazován.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/cs/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) ponechává obrázky beze změny. |

### Poznámky

Obrázky již na cílovém rozlišení nebo pod ním jsou ponechány beze změny; obrázky nejsou nikdy zvětšovány.

Nezpracovávají se: pozadí snímků, výplně buněk tabulek, grafy, SmartArt, GIF obrázky (kvůli zachování animace), SVG a metafile (EMF/WMF) obrázky.

Ořezané oblasti jsou trvale odstraněny a v PowerPointu je nelze obnovit.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` je `None`. |

### Viz také
* třída [`Compress`](/slides/python-net/cs/aspose.slides.lowcode/compress)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* výčet [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression)
* modul [`aspose.slides.lowcode`](/slides/python-net/cs/aspose.slides.lowcode)
* knihovna [`Aspose.Slides`](/slides/python-net)