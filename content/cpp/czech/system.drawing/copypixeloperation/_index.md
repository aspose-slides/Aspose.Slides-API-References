---
title: CopyPixelOperation
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Určuje, jak je barva zdroje při operaci kopírování pixelu kombinována s barvou cíle, aby vznikla výsledná barva.
type: docs
weight: 391
url: /cs/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Určuje, jak je barva zdroje při operaci kopírování pixelu kombinována s barvou cíle, aby vznikla výsledná barva.

```cpp
enum class CopyPixelOperation
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bitmap není zrcadlen. |
| Blackness | 66 | Cílový region je vyplněn pomocí barvy s indexem 0 ve fyzické paletě. |
| NotSourceErase | 1114278 | Barvy zdroje a cíle jsou spojeny operací OR a výsledná barva je poté invertována. |
| NotSourceCopy | 3342344 | Zdrojový region je invertován a poté zkopírován do cíle. |
| SourceErase | 4457256 | Invertované barvy cílového regionu jsou spojeny operací AND s barvami zdrojového regionu. |
| DestinationInvert | 5570569 | Cílový region je invertován. |
| PatInvert | 5898313 | Barvy štětce aktuálně vybraného v kontextu zařízení cíle jsou spojeny operací XOR s barvami cíle. |
| SourceInvert | 6684742 | Barvy zdrojového a cílového regionu jsou spojeny operací XOR. |
| SourceAnd | 8913094 | Barvy zdrojového a cílového regionu jsou spojeny operací AND. |
| MergePaint | 12255782 | Barvy invertovaného zdrojového regionu jsou spojeny operací OR s barvami cílového regionu. |
| MergeCopy | 12583114 | Barvy zdrojového regionu jsou spojeny operací AND s barvami vybraného štětce v kontextu zařízení cíle. |
| SourceCopy | 13369376 | Zdrojový region je přímo zkopírován do cílového regionu. |
| SourcePaint | 15597702 | Barvy zdrojového a cílového regionu jsou spojeny operací OR. |
| PatCopy | 15728673 | Štětec aktuálně vybraný v kontextu zařízení cíle je zkopírován do cílového bitmapu. |
| PatPaint | 16452105 | Barvy štětce aktuálně vybraného v kontextu zařízení cíle jsou spojeny operací OR s barvami invertovaného zdrojového regionu. Výsledek této operace je pak spojen operací OR s barvami cílového regionu. |
| Whiteness | 16711778 | Cílový region je vyplněn pomocí barvy s indexem 1 ve fyzické paletě. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) které jsou vrstveny nad oknem aplikace, jsou zahrnuty do výsledného obrazu. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)