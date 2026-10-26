---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /zh-hant/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

用於外部資源載入參數的介面。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | 匯入的簡報中指定的資源之原始 URI。 |
| [getUri()](#getUri--) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。 |
| [setUri(String value)](#setUri-java.lang.String-) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。 |
| [setData(byte[] data)](#setData-byte---) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)，則設定使用者提供的資源資料。 |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

匯入的簡報中指定的資源之原始 URI。

**回傳值:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。最初它被設定為資源的原始 URI，但可以重新定義為任何值。

**回傳值:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。最初它被設定為資源的原始 URI，但可以重新定義為任何值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)，則設定資源的使用者提供資料。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | byte[] | 資源提供的資料 byte[] |