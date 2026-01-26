---
title: PresentationLockingBehavior
second_title: Aspose.Slides for C++ API Reference
description: "Represents the behavior regarding treating the IPresentation source (file or System::IO::Stream) while loading and working with an instance of IPresentation."
type: docs
weight: 6748
url: /aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum


Represents the behavior regarding treating the [IPresentation](../ipresentation/) source (file or [System::IO::Stream](../../system.io/stream/)) while loading and working with an instance of [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| LoadAndRelease | 0 | The source will be locked only for a time of [IPresentation](../ipresentation/) constructor execution. |
| KeepLocked | 1 | The source will be locked for a whole lifetime of [IPresentation](../ipresentation/) instance, until it will be disposed. |

## Remarks


The source is the parameter passed to the [IPresentation](../ipresentation/) constructor. In the example below, the source is the \"pres.pptx\" file: 


```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```


For this example, the source (\"pres.pptx\" file) will be locked for a [IPresentation](../ipresentation/) instance lifetime, i.e. can't be changed or deleted by the other process. 
## See Also

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)