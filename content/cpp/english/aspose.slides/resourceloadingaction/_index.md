---
title: ResourceLoadingAction
second_title: Aspose.Slides for C++ API Reference
description: Specifies the mode of external resource loading.
type: docs
weight: 6579
url: /aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction enum


Specifies the mode of external resource loading.

```cpp
enum class ResourceLoadingAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) will load external resource as usual. |
| Skip | 1 | [Aspose.Slides](../) will skip loading of external resource. Only link without data will be stored for an image. |
| UserProvided | 2 | [Aspose.Slides](../) will use byte array provided by user in [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) as image data. |

## See Also

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)