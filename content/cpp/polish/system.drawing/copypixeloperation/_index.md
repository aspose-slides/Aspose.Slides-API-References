---
title: CopyPixelOperation
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, w jaki sposób kolor źródłowy w operacji kopiowania pikseli jest łączony z kolorem docelowym, aby uzyskać ostateczny kolor.
type: docs
weight: 391
url: /pl/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Określa, w jaki sposób kolor źródłowy w operacji kopiowania pikseli jest łączony z kolorem docelowym, aby uzyskać ostateczny kolor.

```cpp
enum class CopyPixelOperation
```

### Wartości

| Name | Value | Description |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bitmap nie jest odbity lustrzanie. |
| Blackness | 66 | Region docelowy jest wypełniony przy użyciu koloru o indeksie 0 w fizycznej palecie. |
| NotSourceErase | 1114278 | Kolory źródłowy i docelowy są łączone operacją OR, a powstały kolor jest następnie odwrócony. |
| NotSourceCopy | 3342344 | Region źródłowy jest odwrócony, a następnie kopiowany do regionu docelowego. |
| SourceErase | 4457256 | Odwrócone kolory regionu docelowego są łączone operacją AND z kolorami regionu źródłowego. |
| DestinationInvert | 5570569 | Region docelowy jest odwrócony. |
| PatInvert | 5898313 | Kolory pędzla aktualnie wybranego w kontekście urządzenia docelowego są łączone operacją XOR z kolorami docelowego regionu. |
| SourceInvert | 6684742 | Kolory regionów źródłowego i docelowego są łączone operacją XOR. |
| SourceAnd | 8913094 | Kolory regionów źródłowego i docelowego są łączone operacją AND. |
| MergePaint | 12255782 | Kolory odwróconego regionu źródłowego są łączone operacją OR z kolorami regionu docelowego. |
| MergeCopy | 12583114 | Kolory regionu źródłowego są łączone operacją AND z kolorami wybranego pędzla w kontekście urządzenia docelowego. |
| SourceCopy | 13369376 | Region źródłowy jest kopiowany bezpośrednio do regionu docelowego. |
| SourcePaint | 15597702 | Kolory regionów źródłowego i docelowego są łączone operacją OR. |
| PatCopy | 15728673 | Pędzel aktualnie wybrany w kontekście urządzenia docelowego jest kopiowany do bitmapy docelowej. |
| PatPaint | 16452105 | Kolory pędzla aktualnie wybranego w kontekście urządzenia docelowego są łączone operacją OR z kolorami odwróconego regionu źródłowego. Wynik tej operacji jest łączony operacją OR z kolorami regionu docelowego. |
| Whiteness | 16711778 | Region docelowy jest wypełniony przy użyciu koloru o indeksie 1 w fizycznej palecie. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) które są warstwowane nad oknem aplikacji, są uwzględniane w powstałym obrazie. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)