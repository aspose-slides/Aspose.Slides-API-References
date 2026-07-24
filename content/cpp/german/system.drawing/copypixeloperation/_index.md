---
title: CopyPixelOperation
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie die Quellfarbe bei einer Pixelkopieroperation mit der Zielfarbe kombiniert wird, um eine endgültige Farbe zu erhalten.
type: docs
weight: 391
url: /de/system.drawing/copypixeloperation/
---
## CopyPixelOperation Enum

Specifies how the source color in a pixel copying operation is combined with the destination color to result in a final color.

```cpp
enum class CopyPixelOperation
```

### Werte

| Name | Value | Description |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Das Bitmap ist nicht gespiegelt. |
| Blackness | 66 | Der Zielbereich wird gefüllt, indem die Farbe mit Index 0 in der physischen Palette verwendet wird. |
| NotSourceErase | 1114278 | Die Quell- und Zielfarben werden ODer verknüpft und die resultierende Farbe wird dann invertiert. |
| NotSourceCopy | 3342344 | Der Quellbereich wird invertiert und anschließend in das Ziel kopiert. |
| SourceErase | 4457256 | Die invertierten Farben des Zielbereichs werden mit den Farben des Quellbereichs UND-verknüpft. |
| DestinationInvert | 5570569 | Der Zielbereich wird invertiert. |
| PatInvert | 5898313 | Die Farben des aktuell im Ziel-Device-Context ausgewählten Pinsels werden mit den Farben des Ziels XOR-verknüpft. |
| SourceInvert | 6684742 | Die Farben des Quell- und Zielbereichs werden XOR-verknüpft. |
| SourceAnd | 8913094 | Die Farben des Quell- und Zielbereichs werden UND-verknüpft. |
| MergePaint | 12255782 | Die Farben des invertierten Quellbereichs werden mit den Farben des Zielbereichs ODer. |
| MergeCopy | 12583114 | Die Farben des Quellbereichs werden mit den Farben des im Ziel-Device-Context ausgewählten Pinsels UND-verknüpft. |
| SourceCopy | 13369376 | Der Quellbereich wird direkt in den Zielbereich kopiert. |
| SourcePaint | 15597702 | Die Farben des Quell- und Zielbereichs werden ODer. |
| PatCopy | 15728673 | Der im Ziel-Device-Context aktuell ausgewählte Pinsel wird in das Ziel-Bitmap kopiert. |
| PatPaint | 16452105 | Die Farben des im Ziel-Device-Context aktuell ausgewählten Pinsels werden mit den Farben des invertierten Quellbereichs ODer. Das Ergebnis dieser Operation wird mit den Farben des Zielbereichs ODer. |
| Whiteness | 16711778 | Der Zielbereich wird gefüllt, indem die Farbe mit Index 1 in der physischen Palette verwendet wird. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) die über dem Anwendungsfenster geschichtet sind, werden in das resultierende Bild einbezogen. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)