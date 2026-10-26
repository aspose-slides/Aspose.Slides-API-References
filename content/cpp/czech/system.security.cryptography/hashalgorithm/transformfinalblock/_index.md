---
title: TransformFinalBlock()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Zpracovává poslední blok dat a vypočítá hash.
type: docs
weight: 79
url: /cs/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metoda


Zpracovává poslední blok dat a vypočítá hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro čtení dat z. |
| inputOffset | int | Posun vstupního bufferu. |
| inputCount | int | Počet bytů ke zpracování. |

### Návratová hodnota

Hash vypočítaný pro celou datovou sekvenci.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [HashAlgorithm](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)