---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API Reference
description: Creates new PresentationInfo object from file and binds presentation to it.
type: docs
weight: 27
url: /cpp/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo([System::String](../../../system/string/)) method


Creates new [PresentationInfo](../../presentationinfo/) object from file and binds presentation to it.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) file. |

### Return Value

[Presentation](../../presentation/) info binded to presentation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## PresentationFactory::GetPresentationInfo([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>) method


Creates new [PresentationInfo](../../presentationinfo/) object from stream and binds presentation to it. Gets info about presentation in specified stream.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) stream. |

### Return Value

[Presentation](../../presentation/) info binded to presentation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [Stream](../../../system.io/stream/)
* Class [PresentationFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
