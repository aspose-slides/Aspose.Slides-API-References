---
title: IResourceLoadingCallback
second_title: Aspose.Slides für Java API-Referenz
description: Callback-Interface zur Verwaltung des Ladens externer Ressourcen.
type: docs
url: /de/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback-Interface zur Verwaltung des Ladens externer Ressourcen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback-Methode, die das Laden externer Ressourcen reguliert. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Callback-Methode, die das Laden externer Ressourcen reguliert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Die ladenden Ressourcendaten [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Rückgabewert:**
int - Die Entscheidung über das Laden der Ressource [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).