---
title: TransformBlock()
second_title: Aspose.Slides for C++ API Reference
description: Processes block of data and copies data to output array.
type: docs
weight: 1
url: /cpp/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Processes block of data and copies data to output array.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | int | Input buffer offset. |
| inputCount | int | Number of bytes to process. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Output buffer to copy data into; nullptr to do no copying. |
| outputOffset | int | Output buffer offset. |

### Return Value

Number of bytes written.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)