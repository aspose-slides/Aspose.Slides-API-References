---
title: Seek()
second_title: Aspose.Slides for C++ API Reference
description: Sets the position within the current stream
type: docs
weight: 131
url: /cpp/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) method


Sets the position within the current stream

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | A byte offset relative to the origin parameter **int64_t** |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | A value of type [System::IO::SeekOrigin](../../../system.io/seekorigin/) indicating the reference point used to obtain the new position |

### Return Value

The new position within the current stream **int64_t**

## See Also

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [IStreamWrapper](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)