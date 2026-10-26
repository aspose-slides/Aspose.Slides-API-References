---
title: TransformBlock()
second_title: Aspose.Slides for C++ API referencia
description: Feldolgozza az adatblokkot, és átmásolja az adatokat a kimeneti tömbbe.
type: docs
weight: 53
url: /hu/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) metódus

Feldolgozza az adatblokkot, és átmásolja az adatokat a kimeneti tömbbe.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) az adatok olvasásához. |
| inputOffset | **int32_t** | Bemeneti puffer eltolása. |
| inputCount | **int32_t** | A feldolgozandó bájtok száma. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kimeneti puffer, amelybe az adatokat másoljuk; nullptr, ha nem másolunk. |
| outputOffset | **int32_t** | Kimeneti puffer eltolása. |

### Visszatérési érték

Az írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ToBase64Transform](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)