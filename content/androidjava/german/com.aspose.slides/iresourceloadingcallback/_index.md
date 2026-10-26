---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /de/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback-Schnittstelle zur Verwaltung des Ladens externer Ressourcen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback-Methode, die das Laden externer Ressourcen regelt. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Callback-Methode, die das Laden externer Ressourcen regelt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Die zu ladenden Ressourcendaten [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Rückgabewert:**
int - Die Entscheidung zum Laden der Ressource [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).