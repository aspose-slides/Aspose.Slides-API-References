---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API Reference
description: Processes last block of data and calculates output value.
type: docs
weight: 14
url: /system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method


Processes last block of data and calculates output value.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int | Input buffer offset. |
| inputCount | int | Number of bytes to process. |

### Return Value

Output calculated for the whole input sequence.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)