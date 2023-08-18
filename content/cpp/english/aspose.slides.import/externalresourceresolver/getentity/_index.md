---
title: GetEntity()
second_title: Aspose.Slides for C++ API Reference
description: Maps a URI to an object containing the actual resource.
type: docs
weight: 14
url: /aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) method


Maps a URI to an object containing the actual resource.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolute URI to the object. |

### Return Value

A [System::IO::Stream](../../../system.io/stream/) object or null if resource cannot be streamed.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)