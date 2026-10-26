---
title: TransformBlock()
second_title: Aspose.Slides för C++ API-referens
description: Bearbetar ett block med data och kopierar data till utdatabufferten.
type: docs
weight: 53
url: /sv/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method

Bearbetar ett block med data och kopierar data till utdatabufferten.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | **int32_t** | Input buffer offset. |
| inputCount | **int32_t** | Number of bytes to process. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Utdatabuffert för att kopiera data till; nullptr för att inte kopiera. |
| outputOffset | **int32_t** | Output buffer offset. |

### Returvärde

Antal skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ToBase64Transform](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)