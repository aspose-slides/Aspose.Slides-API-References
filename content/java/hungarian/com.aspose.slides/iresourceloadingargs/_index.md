---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Külső erőforrás betöltési argumentumok interfésze.
type: docs
url: /hu/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Külső erőforrás betöltési argumentumok interfésze.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Az erőforrás eredeti URI-ja, ahogyan az importált prezentációban meg van adva. |
| [getUri()](#getUri--) | Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) értéket ad vissza. |
| [setUri(String value)](#setUri-java.lang.String-) | Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) értéket ad vissza. |
| [setData(byte[] data)](#setData-byte---) | Beállítja a felhasználó által megadott erőforrás adatot, amely akkor használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) értéket ad vissza. |

### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

Az erőforrás eredeti URI-ja, ahogyan az importált prezentációban meg van adva.

**Visszatér:**
java.lang.String

### getUri() {#getUri--}
```
public abstract String getUri()
```

Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) értékét adja vissza. Kezdetben az erőforrás eredeti URI-jára van beállítva, de tetszőleges értékre felülírható.

**Visszatér:**
java.lang.String

### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

Az erőforrás URI-ja, amely a letöltéshez használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) értékét adja vissza. Kezdetben az erőforrás eredeti URI-jára van beállítva, de tetszőleges értékre felülírható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

Beállítja a felhasználó által megadott erőforrás adatot, amely akkor használatos, ha [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) értékét adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Az erőforrás megadott adata byte[] |