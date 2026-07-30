---
title: TransformFinalBlock()
second_title: Aspose.Slides pro C++ - reference API
description: Zpracuje poslední blok dat a vypočítá výstupní hodnotu.
type: docs
weight: 14
url: /cs/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metoda

Zpracuje poslední blok dat a vypočítá výstupní hodnotu.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) k přečtení dat z. |
| inputOffset | int | Posun vstupního bufferu. |
| inputCount | int | Počet bajtů ke zpracování. |

### Návratová hodnota

Výstup vypočítaný pro celou vstupní sekvenci.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICryptoTransform](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)