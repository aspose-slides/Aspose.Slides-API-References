---
title: TransformBlock()
second_title: Aspose.Slides C++ API Referencia
description: Feldolgozza az adatblokkot és átmásolja az adatot a kimeneti tömbbe.
type: docs
weight: 66
url: /hu/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metódus

Feldolgozza az adatblokkot és átmásolja az adatot a kimeneti tömbbe.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az adat olvasásához. |
| inputOffset | int | Bemeneti puffer eltolása. |
| inputCount | int | A feldolgozandó bájtok száma. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kimeneti puffer, ahová az adatot másolni kell; nullptr, ha nem kell másolni. |
| outputOffset | int | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [HashAlgorithm](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)