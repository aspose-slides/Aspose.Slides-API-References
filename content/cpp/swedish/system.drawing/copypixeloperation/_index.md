---
title: CopyPixelOperation
second_title: Aspose.Slides för C++ API-referens
description: Anger hur källfärgen i en pixelkopieringsoperation kombineras med målfärgen för att resultera i en slutlig färg.
type: docs
weight: 391
url: /sv/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Anger hur källfärgen i en pixelkopieringsoperation kombineras med målfärgen för att resultera i en slutlig färg.

```cpp
enum class CopyPixelOperation
```

### Values

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bitmappen är inte speglad. |
| Blackness | 66 | Målregionen fylls genom att använda färgen med index 0 i den fysiska paletten. |
| NotSourceErase | 1114278 | Källa- och målfärgerna OR-as och den resulterande färgen inverteras sedan. |
| NotSourceCopy | 3342344 | Källregionen inverteras och kopieras sedan till målet. |
| SourceErase | 4457256 | De inverterade färgerna i målregionen AND-as med färgerna i källregionen. |
| DestinationInvert | 5570569 | Målregionen inverteras. |
| PatInvert | 5898313 | Färgerna på den för närvarande valda penseln i mål-enhetskontexten XOR-as med färgerna i målet. |
| SourceInvert | 6684742 | Färgerna i käll- och målregionerna XOR-as. |
| SourceAnd | 8913094 | Färgerna i käll- och målregionerna AND-as. |
| MergePaint | 12255782 | Färgerna i den inverterade källregionen OR-as med färgerna i målregionen. |
| MergeCopy | 12583114 | Färgerna i källregionen AND-as med färgerna på den valda penseln i mål-enhetskontexten. |
| SourceCopy | 13369376 | Källregionen kopieras direkt till målregionen. |
| SourcePaint | 15597702 | Färgerna i käll- och målregionerna OR-as. |
| PatCopy | 15728673 | Den för närvarande valda penseln i mål-enhetskontexten kopieras till mål-bitmappen. |
| PatPaint | 16452105 | Färgerna på den för närvarande valda penseln i mål-enhetskontexten OR-as med färgerna i den inverterade källregionen. Resultatet av denna operation OR-as sedan med färgerna i målregionen. |
| Whiteness | 16711778 | Målregionen fylls genom att använda färgen med index 1 i den fysiska paletten. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) som är lagerade ovanpå applikationens fönster inkluderas i den resulterande bilden. |

## Se också

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)