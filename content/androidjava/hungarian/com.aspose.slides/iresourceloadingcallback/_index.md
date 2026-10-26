---
title: IResourceLoadingCallback
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Visszahívási interfész, amely a külső erőforrások betöltésének kezelésére szolgál.
type: docs
url: /hu/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Visszahívási interfész, amely a külső erőforrások betöltésének kezelésére szolgál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Visszahívási metódus, amely szabályozza a külső erőforrások betöltését. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Visszahívási metódus, amely szabályozza a külső erőforrások betöltését.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Az erőforrás betöltési adata [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Visszatérési érték:**
int - Az erőforrás betöltésének döntése [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).