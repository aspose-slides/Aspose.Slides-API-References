---
title: compress_images method
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Zmniejsza rozdzielczość obrazów w prezentacji i usuwa ich przycięte obszary,
            podobnie jak funkcja „Compress Pictures” w programie PowerPoint zastosowana do wszystkich obrazów.
            Przetwarzane są obrazy na slajdach, slajdach układu i slajdach podstawowych, w tym obrazy wewnątrz grup kształtów
            oraz wypełnienia obrazami kształtów.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation) | Prezentacja do przetworzenia. |
| resolution | [`PicturesCompression`](/slides/python-net/pl/aspose.slides.export/picturescompression) | Docelowa rozdzielczość względem rozmiaru, w którym wyświetlane jest każde zdjęcie.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/pl/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) pozostawia obrazy niezmienione. |

### Uwagi

Obrazy już o docelowej rozdzielczości lub niższej pozostają niezmienione; obrazy nigdy nie są powiększane.

Nie przetwarzane: tła slajdów, wypełnienia komórek tabel, wykresy, SmartArt, obrazy GIF (aby zachować animację), obrazy SVG oraz metaplików (EMF/WMF).

Obcięte obszary są usuwane trwale i nie mogą być przywrócone w programie PowerPoint.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` jest `None`. |



### Zobacz także
* klasa [`Compress`](/slides/python-net/pl/aspose.slides.lowcode/compress)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* wyliczenie [`PicturesCompression`](/slides/python-net/pl/aspose.slides.export/picturescompression)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)