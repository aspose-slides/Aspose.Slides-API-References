---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback-interface die wordt gebruikt om het laden van externe resources te beheren.
type: docs
url: /nl/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback-interface die wordt gebruikt om het laden van externe resources te beheren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback-methode die het laden van externe resources reguleert. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Callback-methode die het laden van externe resources reguleert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | De laadresourcegegevens [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Retour:**
int - De beslissing over het laden van de resource [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).