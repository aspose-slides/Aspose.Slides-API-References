---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interfaz de devolución de llamada utilizada para gestionar la carga de recursos externos.
type: docs
url: /es/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Interfaz de devolución de llamada utilizada para gestionar la carga de recursos externos.
## Métodos

| Método | Descripción |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Método de devolución de llamada que regula la carga de recursos externos. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Método de devolución de llamada que regula la carga de recursos externos.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Los datos del recurso de carga [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Devuelve:**
int - La decisión de carga del recurso [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).