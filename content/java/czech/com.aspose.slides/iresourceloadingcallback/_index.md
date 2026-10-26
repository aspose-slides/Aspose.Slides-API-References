---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Rozhraní Callback používané k řízení načítání externích zdrojů.
type: docs
url: /cs/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Rozhraní Callback používané k řízení načítání externích zdrojů.
## Metody

| Metoda | Popis |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Metoda Callback, která reguluje načítání externích zdrojů. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Metoda Callback, která reguluje načítání externích zdrojů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Data načítaného zdroje [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Návratová hodnota:**
int - Rozhodnutí o načítání zdroje [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).