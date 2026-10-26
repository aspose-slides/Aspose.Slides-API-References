---
title: TransformBlock()
second_title: Aspose.Slides pro C++ API – referenční příručka
description: Zpracuje blok dat a zkopíruje data do výstupního pole.
type: docs
weight: 1
url: /cs/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metoda

Zpracuje blok dat a zkopíruje data do výstupního pole.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k načtení dat z. |
| inputOffset | int | Posun vstupního bufferu. |
| inputCount | int | Počet bajtů ke zpracování. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Výstupní buffer, do kterého se kopírují data; nullptr pro žádné kopírování. |
| outputOffset | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICryptoTransform](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)