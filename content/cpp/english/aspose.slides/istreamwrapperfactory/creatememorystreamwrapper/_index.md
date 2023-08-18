---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Creates MemoryStream wrapper.
type: docs
weight: 1
url: /aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() method


Creates MemoryStream wrapper.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```


### Return Value

Stream wrapper for COM interface [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) method


Creates MemoryStream wrapper based on the specified byte array.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte array **uint8_t**[] |

### Return Value

Stream wrapper for COM interface [IStreamWrapper](../../istreamwrapper/)

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)