---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Callback-interface die wordt gebruikt om het laden van externe bronnen te beheren.
type: docs
url: /nl/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Callback-interface die wordt gebruikt om het laden van externe bronnen te beheren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback-methode die het laden van externe bronnen reguleert. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Callback-methode die het laden van externe bronnen reguleert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | De gegevens van de te laden bron [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Retour:**
int - De beslissing over het laden van de bron [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).