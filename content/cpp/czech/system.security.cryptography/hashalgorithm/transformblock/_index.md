---
title: TransformBlock()
second_title: Aspose.Slides pro C++ API Reference
description: Zpracovává blok dat a kopíruje data do výstupního pole.
type: docs
weight: 66
url: /cs/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metoda

Zpracovává blok dat a kopíruje data do výstupního pole.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) ke čtení dat z. |
| inputOffset | int | Posun vstupního bufferu. |
| inputCount | int | Počet bajtů ke zpracování. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Výstupní buffer, do kterého se kopírují data; nullptr pro žádné kopírování. |
| outputOffset | int | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [HashAlgorithm](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)