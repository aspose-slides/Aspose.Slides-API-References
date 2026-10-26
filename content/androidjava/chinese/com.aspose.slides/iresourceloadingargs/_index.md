---
title: IResourceLoadingArgs
second_title: Aspose.Slides Android 版 Java API 参考
description: 外部资源加载参数的接口。
type: docs
url: /zh/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

外部资源加载参数的接口。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Original URI of the resource as specified in imported presentation. |
| [getUri()](#getUri--) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Sets user provided data of the resource which used if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |

### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

导入演示文稿中指定的资源的原始 URI。

**返回值:**  
java.lang.String

### getUri() {#getUri--}
```
public abstract String getUri()
```

如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，则用于下载的资源 URI。初始时它设置为资源的原始 URI，但可以重新定义为任意值。

**返回值:**  
java.lang.String

### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 返回 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，则用于下载的资源 URI。初始时它设置为资源的原始 URI，但可以重新定义为任意值。

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
| data | byte[] | 资源的提供数据 byte[] |