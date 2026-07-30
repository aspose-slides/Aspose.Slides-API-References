---
title: TransformBlock()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zpracovává blok dat a kopíruje data do výstupního pole.
type: docs
weight: 53
url: /cs/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) metoda

Zpracovává blok dat a kopíruje data do výstupního pole.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro čtení dat z. |
| inputOffset | **int32_t** | Posun vstupního bufferu. |
| inputCount | **int32_t** | Počet bajtů ke zpracování. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Výstupní buffer, do kterého se mají data kopírovat; nullptr pro žádné kopírování. |
| outputOffset | **int32_t** | Posun výstupního bufferu. |

### Návratová hodnota

Počet zapsaných bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ToBase64Transform](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)