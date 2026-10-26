---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Interfaccia di callback usata per gestire il caricamento di risorse esterne.
type: docs
url: /it/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Interfaccia di callback usata per gestire il caricamento di risorse esterne.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Metodo di callback che regola il caricamento delle risorse esterne. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Metodo di callback che regola il caricamento delle risorse esterne.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | I dati della risorsa di caricamento [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Restituisce:**
int - La decisione di caricamento della risorsa [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).