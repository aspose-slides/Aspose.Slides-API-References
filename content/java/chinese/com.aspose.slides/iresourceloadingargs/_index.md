---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /zh/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

用于外部资源加载参数的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | 在导入的演示文稿中指定的资源的原始 URI。 |
| [getUri()](#getUri--) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，则用于下载的资源 URI。 |
| [setUri(String value)](#setUri-java.lang.String-) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，则用于下载的资源 URI。 |
| [setData(byte[] data)](#setData-byte---) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)，则使用用户提供的资源数据。 |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


在导入的演示文稿中指定的资源的原始 URI。

**返回值:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，则用于下载的资源 URI。最初它被设置为资源的原始 URI，但可以重新定义为任意值。

**返回值:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，则用于下载的资源 URI。最初它被设置为资源的原始 URI，但可以重新定义为任意值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)，则使用用户提供的资源数据。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 资源提供的 byte[] 数据 |