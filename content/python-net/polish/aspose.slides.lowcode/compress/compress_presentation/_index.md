---
title: compress_presentation method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Zmniejsza rozmiar prezentacji, stosując wszystkie dostępne kroki kompresji:
            
* Usuwa nieużywane slajdy master **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Usuwa nieużywane slajdy układu **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Zachowuje tylko glify rzeczywiście użyte w osadzonych czcionkach **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Zmniejsza rozdzielczość obrazów do 150 DPI i usuwa przycięte obszary obrazów **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/pl/aspose.slides/presentation) | Prezentacja do skompresowania. |

### Uwagi

Aby dostosować kompresję, na przykład użyć innej rozdzielczości obrazów lub pominąć krok, wywołaj wymienione powyżej metody indywidualnie zamiast tej. Przycięte obszary obrazów są usuwane trwale i nie mogą zostać przywrócone w programie PowerPoint.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` jest `None`. |

### Zobacz także
* klasa [`Compress`](/slides/python-net/pl/aspose.slides.lowcode/compress)
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)