---
title: TransformBlock()
second_title: Aspose.Slides för C++ API-referens
description: Bearbetar ett block med data och kopierar data till utdataarrayen.
type: docs
weight: 66
url: /sv/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metod


Bearbetar ett block med data och kopierar data till utdata-arrayen.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | int | Offset för inmatningsbuffert. |
| inputCount | int | Antalet byte att bearbeta. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Utdata-buffer att kopiera data till; nullptr för att inte kopiera. |
| outputOffset | int | Offset för utdata-buffer. |

### Returvärde

Antalet skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)