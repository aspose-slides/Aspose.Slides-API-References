---
title: TemplateContext
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una interfaz de objeto modelo para un motor de plantillas.
type: docs
url: /es/com.aspose.slides/templatecontext/
---
**Herencia:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Representa una interfaz de objeto modelo para un motor de plantillas.
## Métodos

| Método | Descripción |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Creates a child template context. |
| [getObject()](#getObject--) | Returns the model object. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the host document. |
| [getLocal()](#getLocal--) | Returns local storage of the current template context. |
| [getGlobal()](#getGlobal--) | Returns global storage of the host document. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Crea un contexto de plantilla hijo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subModel | TSubModel | Objeto modelo hijo. |

**Devuelve:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nuevo contexto de plantilla con el modelo dado y la colección de salida del padre y el almacenamiento global.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Devuelve el objeto del modelo. Solo lectura Object.

**Devuelve:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Devuelve la colección de elementos de salida del documento anfitrión. Solo lectura [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Devuelve:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Devuelve el almacenamiento local del contexto de plantilla actual. Solo lectura [Storage](../../com.aspose.slides/storage).

**Devuelve:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Devuelve el almacenamiento global del documento anfitrión. Solo lectura [Storage](../../com.aspose.slides/storage).

**Devuelve:**
[Storage](../../com.aspose.slides/storage)