---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Referencia
description: Callback interfész, amely a külső erőforrások betöltésének kezelésére szolgál.
type: docs
url: /hu/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback interfész, amely a külső erőforrások betöltésének kezelésére szolgál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback metódus, amely szabályozza a külső erőforrások betöltését. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Callback metódus, amely szabályozza a külső erőforrások betöltését.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | A betöltött erőforrás adatai [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Visszatérési érték:**
int - A forrás betöltésének döntése [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).