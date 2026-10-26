---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Återuppringningsgränssnitt som används för att hantera inläsning av externa resurser.
type: docs
url: /sv/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Återuppringningsgränssnitt som används för att hantera inläsning av externa resurser.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Återuppringningsmetod som reglerar inläsning av externa resurser. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Återuppringningsmetod som reglerar inläsning av externa resurser.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Data för den laddande resursen [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Returnerar:**
int - Beslutet för resursinläsning [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).