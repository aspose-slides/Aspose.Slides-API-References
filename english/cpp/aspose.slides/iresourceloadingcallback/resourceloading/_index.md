---
title: ResourceLoading()
second_title: Aspose.Slides for C++ API Reference
description: Callback method which regulates external resources loading.
type: docs
weight: 1
url: /cpp/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading([System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\>) method


Callback method which regulates external resources loading.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | The loading resource data [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Return Value

The resource loading decision [ResourceLoadingAction](../../resourceloadingaction/).

## See Also

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IResourceLoadingArgs](../../iresourceloadingargs/)
* Class [IResourceLoadingCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
