---
title: TransformFinalBlock()
second_title: Aspose.Slides för C++ API-referens
description: Behandlar sista datablocket och beräknar hash.
type: docs
weight: 79
url: /sv/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metod


Behandlar sista datablocket och beräknar hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | int | Indatabuffertsförskjutning. |
| inputCount | int | Antal byte att bearbeta. |

### Returvärde

Hash beräknad för hela datasekvensen.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [HashAlgorithm](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)