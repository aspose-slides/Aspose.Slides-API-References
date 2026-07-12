---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Harici kaynak yükleme argümanları için arayüz.
type: docs
url: /tr/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Harici kaynak yükleme argümanları için arayüz.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | İçe aktarılan sunumda belirtildiği gibi kaynağın orijinal URI'si. |
| [getUri()](#getUri--) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) döndürürse, indirme için kullanılan kaynağın URI'si. |
| [setUri(String value)](#setUri-java.lang.String-) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) döndürürse, indirme için kullanılan kaynağın URI'si. |
| [setData(byte[] data)](#setData-byte---) | Kullanıcı tarafından sağlanan kaynağın verisini ayarlar, bu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) döndürürse kullanılır. |

### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

İçe aktarılan sunumda belirtildiği gibi kaynağın orijinal URI'si.

**Döndürür:**
java.lang.String

### getUri() {#getUri--}
```
public abstract String getUri()
```

[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) döndürürse, indirme için kullanılan kaynağın URI'si. Başlangıçta kaynağın orijinal URI'sine ayarlanır, ancak herhangi bir değere yeniden tanımlanabilir.

**Döndürür:**
java.lang.String

### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) döndürürse, indirme için kullanılan kaynağın URI'si. Başlangıçta kaynağın orijinal URI'sine ayarlanır, ancak herhangi bir değere yeniden tanımlanabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

Kullanıcı tarafından sağlanan kaynağın verisini ayarlar, bu [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) döndürürse kullanılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | byte[] | Kaynağın sağlanan verisi byte[] |
