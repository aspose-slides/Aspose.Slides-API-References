---
title: TransformBlock()
second_title: Aspose.Slides för C++ API-referens
description: Bearbetar ett block med data och kopierar data till utdatabufferten.
type: docs
weight: 1
url: /sv/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Bearbetar ett block med data och kopierar data till utdataarray.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) att läsa data från. |
| inputOffset | int | Inmatningsbuffertens offset. |
| inputCount | int | Antal byte att behandla. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Utdatabuffert att kopiera data till; nullptr för att inte kopiera. |
| outputOffset | int | Utdatabuffertens offset. |

### Returvärde

Antal byte skrivna.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [ICryptoTransform](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)