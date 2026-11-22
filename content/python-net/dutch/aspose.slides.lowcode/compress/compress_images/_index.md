---
title: compress_images method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Vermindert de resolutie van afbeeldingen in de presentatie en verwijdert hun bijgesneden delen,
            vergelijkbaar met PowerPoint's "Compress Pictures" toegepast op alle afbeeldingen.
            Afbeeldingen op dia's, lay-outdia's en masterdia's worden verwerkt, inclusief afbeeldingen binnen groepvormen
            en afbeeldingvullingen van vormen.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) | De presentatie om te verwerken. |
| resolution | [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression) | Doelresolutie relatief ten opzichte van de grootte waarin elke afbeelding wordt weergegeven.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/nl/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) laat afbeeldingen ongewijzigd. |

### Opmerkingen

Afbeeldingen die al op of onder de doelresolutie zijn, blijven ongewijzigd; afbeeldingen worden nooit opgewaardeerd.

Niet verwerkt: dia-achtergronden, celvullingen van tabellen, grafieken, SmartArt, GIF-afbeeldingen (om animatie te behouden), SVG- en metafile (EMF/WMF) afbeeldingen.

Bijsneden delen worden permanent verwijderd en kunnen niet in PowerPoint worden hersteld.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |

### Zie ook
* klasse [`Compress`](/slides/python-net/nl/aspose.slides.lowcode/compress)
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* enumeratie [`PicturesCompression`](/slides/python-net/nl/aspose.slides.export/picturescompression)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)