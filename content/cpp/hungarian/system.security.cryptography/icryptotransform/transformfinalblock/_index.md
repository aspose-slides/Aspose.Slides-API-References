---
title: TransformFinalBlock()
second_title: Aspose.Slides C++ API referenciája
description: Feldolgozza az adat utolsó blokkját és kiszámítja a kimeneti értéket.
type: docs
weight: 14
url: /hu/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metódus


Feldolgozza az adat utolsó blokkját és kiszámítja a kimeneti értéket.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az adat beolvasásához. |
| inputOffset | int | Bemeneti puffer eltolás. |
| inputCount | int | Feldolgozandó bájtok száma. |

### Visszatérési érték

A teljes bemeneti sorozatra számított kimenet.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)