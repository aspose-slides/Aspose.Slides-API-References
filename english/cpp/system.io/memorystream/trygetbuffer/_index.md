---
title: TryGetBuffer()
second_title: Aspose.Slides for C++ API Reference
description: Returns the array of unsigned bytes from which this stream was created.
type: docs
weight: 170
url: /cpp/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) method


Returns the array of unsigned bytes from which this stream was created.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | byte array - out paramter. When this method returns true, the byte array segment from which this stream was created; when this method returns false, this parameter is set to default. |

### Return Value

True if the conversion succeeded.

## See Also

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)