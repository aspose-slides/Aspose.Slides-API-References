---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Interface for external resource loading arguments.
type: docs
weight: 995
url: /java/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interface for external resource loading arguments.
## Methods

| Method | Description |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Original URI of the resource as specified in imported presentation. |
| [getUri()](#getUri--) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Sets user provided data of the resource which used if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Original URI of the resource as specified in imported presentation.

**Returns:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Initially it's set to original URI of the resource, but can be redefined to any value.

**Returns:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Initially it's set to original URI of the resource, but can be redefined to any value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Sets user provided data of the resource which used if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Provided data of the resource byte[] |

