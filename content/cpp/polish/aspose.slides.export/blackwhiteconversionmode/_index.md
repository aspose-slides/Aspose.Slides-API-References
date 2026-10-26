---
title: BlackWhiteConversionMode
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Udostępnia opcje, które kontrolują, jak obrazy slajdów będą konwertowane na obrazy dwuwartościowe.
type: docs
weight: 820
url: /pl/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Udostępnia opcje, które kontrolują, jak obrazy slajdów będą konwertowane na obrazy dwuwartościowe.

```cpp
enum class BlackWhiteConversionMode
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Default | 0 | Określa brak algorytmu konwersji. Zostanie użyty algorytm zaimplementowany w kodeku TIFF. (Default) |
| Dithering | 1 | Określa algorytm ditheringu (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Określa algorytm ditheringu Floyd-Steinberg. |
| Auto | 3 | Określa automatycznie obliczany algorytm progowy (Otsu). |
| AutoOtsu | 4 | Określa automatycznie obliczany progowy algorytm Otsu. |
| Threshold25 | 5 | Określa statyczny algorytm progowy (25%). |
| Threshold50 | 6 | Określa statyczny algorytm progowy (50%). |
| Threshold75 | 7 | Określa statyczny algorytm progowy (75%). |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)