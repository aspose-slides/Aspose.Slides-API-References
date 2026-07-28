---
title: TransformBlock()
second_title: Aspose.Slides C++ API referenciája
description: Feldolgozza az adatblokkot és átmásolja az adatot a kimeneti tömbbe.
type: docs
weight: 1
url: /hu/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metódus


Feldolgozza az adatblokkot és átmásolja az adatot a kimeneti tömbbe.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az adat olvasásához. |
| inputOffset | int | Bemeneti puffer eltolás. |
| inputCount | int | Feldolgozandó bájtok száma. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kimeneti puffer, amelybe az adat másolódik; nullptr a másolás elhagyásához. |
| outputOffset | int | Kimeneti puffer eltolás. |

### Visszatérési érték

A leírt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ICryptoTransform](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)