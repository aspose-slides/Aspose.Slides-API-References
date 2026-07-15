---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /zh-hant/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

外部資源載入參數的介面。

## 方法

| Method | Description |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | 匯入簡報中指定的資源之原始 URI。 |
| [getUri()](#getUri--) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。 |
| [setUri(String value)](#setUri-java.lang.String-) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。 |
| [setData(byte[] data)](#setData-byte---) | 如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)，則設定使用者提供的資源資料。 |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


匯入簡報中指定的資源之原始 URI。

**傳回值:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。最初設定為資源的原始 URI，但可重新定義為任何值。

**傳回值:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)，則用於下載的資源 URI。最初設定為資源的原始 URI，但可重新定義為任何值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


如果 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 回傳 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)，則設定使用者提供的資源資料。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 提供的資源資料 byte[] |