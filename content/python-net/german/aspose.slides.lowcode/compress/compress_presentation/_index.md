---
title: compress_presentation method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Reduziert die Größe einer Präsentation, indem alle verfügbaren Komprimierungsschritte angewendet werden:
            
* Entfernt ungenutzte Master-Folien **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Entfernt ungenutzte Layout-Folien **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Behält nur die tatsächlich in eingebetteten Schriftarten verwendeten Glyphen **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Reduziert die Bildauflösung auf 150 DPI und löscht beschnittene Bildbereiche **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/de/aspose.slides/presentation) | Die zu komprimierende Präsentation. |

### Hinweise

Um die Komprimierung anzupassen, zum Beispiel um eine andere Bildauflösung zu verwenden oder einen Schritt zu überspringen, rufen Sie die oben aufgeführten Methoden einzeln statt dieser auf. Beschnittene Bildbereiche werden dauerhaft entfernt und können in PowerPoint nicht wiederhergestellt werden.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` ist `None`. |



### Siehe auch
* Klasse [`Compress`](/slides/python-net/de/aspose.slides.lowcode/compress)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* Bibliothek [`Aspose.Slides`](/slides/python-net)