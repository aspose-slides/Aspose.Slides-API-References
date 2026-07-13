---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /sv/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback-gränssnitt som används för att hantera inläsning av externa resurser.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback-metod som reglerar inläsning av externa resurser. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Callback-metod som reglerar inläsning av externa resurser.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Den laddande resursdatat [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Returnerar:**
int - Resursladdningsbeslutet [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).