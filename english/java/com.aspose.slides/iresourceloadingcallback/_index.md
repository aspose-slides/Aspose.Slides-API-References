---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
weight: 996
url: /java/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback interface used to manage external resources loading.
## Methods

| Method | Description |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback method which regulates external resources loading. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Callback method which regulates external resources loading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | The loading resource data [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Returns:**
int - The resource loading decision [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).
