---
title: TransformFinalBlock()
second_title: Aspose.Slides för C++ API-referens
description: Bearbetar det sista blocket av data och beräknar utdatavärdet.
type: docs
weight: 14
url: /sv/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metod


Bearbetar sista blocket av data och beräknar utdatavärdet.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att läsa data från. |
| inputOffset | int | Inmatningsbuffertens offset. |
| inputCount | int | Antal byte att bearbeta. |

### Returvärde

Utdata beräknad för hela inmatningssekvensen.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICryptoTransform](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)