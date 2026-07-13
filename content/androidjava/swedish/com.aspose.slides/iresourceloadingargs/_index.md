---
title: IResourceLoadingArgs
second_title: Aspose.Slides för Android via Java API-referens
description: Gränssnitt för externa resurshämtningsargument.
type: docs
url: /sv/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Gränssnitt för externa resurshämtningsargument.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Ursprunglig URI för resursen som angavs i den importerade presentationen. |
| [getUri()](#getUri--) | URI för resursen som används för nedladdning om [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returnerar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI för resursen som används för nedladdning om [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returnerar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Anger data som tillhandahålls av användaren för resursen som används om [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returnerar [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Ursprunglig URI för resursen som angavs i den importerade presentationen.

**Returnerar:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI för resursen som används för nedladdning om [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returnerar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Initialt är den inställd på den ursprungliga URI:n för resursen, men kan omdefinieras till vilket värde som helst.

**Returnerar:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI för resursen som används för nedladdning om [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returnerar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Initialt är den inställd på den ursprungliga URI:n för resursen, men kan omdefinieras till vilket värde som helst.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Anger data som tillhandahålls av användaren för resursen som används om [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returnerar [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Tillhandahållen data för resursen byte[] |