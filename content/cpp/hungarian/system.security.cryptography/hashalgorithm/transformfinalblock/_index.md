---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API referencia
description: Feldolgozza az adat utolsó blokkját és kiszámítja a hash-et.
type: docs
weight: 79
url: /hu/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metódus

Feldolgozza az adat utolsó blokkját és kiszámítja a hash-et.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az adatok olvasásához. |
| inputOffset | int | Bemeneti buffer eltolása. |
| inputCount | int | Feldolgozandó bájtok száma. |

### Visszatérési érték

Az egész adat sorozatra kiszámított hash.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [HashAlgorithm](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)