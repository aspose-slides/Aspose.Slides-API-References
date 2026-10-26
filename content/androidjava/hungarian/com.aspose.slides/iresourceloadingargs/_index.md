---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Külső erőforrás betöltési argumentumok felületje.
type: docs
url: /hu/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Külső erőforrás betöltési argumentumok felületje.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Az erőforrás eredeti URI-ja a importált prezentációban megadott módon. |
| [getUri()](#getUri--) | Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) visszaadja [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) visszaadja [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Beállítja a felhasználó által biztosított erőforrás adatot, amely akkor használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) visszaadja [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Az erőforrás eredeti URI-ja a importált prezentációban megadott módon.

**Visszatér:**  
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) visszaadja [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Kezdetben az erőforrás eredeti URI-jára van beállítva, de bármilyen értékre felülírható.

**Visszatér:**  
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) visszaadja [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Kezdetben az erőforrás eredeti URI-jára van beállítva, de bármilyen értékre felülírható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Beállítja a felhasználó által biztosított erőforrás adatot, amely akkor használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) visszaadja [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Az erőforrás biztosított adata byte[] |