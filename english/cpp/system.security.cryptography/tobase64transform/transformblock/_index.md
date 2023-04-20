---
title: TransformBlock()
second_title: Aspose.Slides for C++ API Reference
description: Processes block of data and copies data to output array.
type: docs
weight: 53
url: /cpp/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method


Processes block of data and copies data to output array.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read data from. |
| inputOffset | **int32_t** | Input buffer offset. |
| inputCount | **int32_t** | Number of bytes to process. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Output buffer to copy data into; nullptr to do no copying. |
| outputOffset | **int32_t** | Output buffer offset. |

### Return Value

Number of bytes written.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)