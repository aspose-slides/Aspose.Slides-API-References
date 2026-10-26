---
title: ResourceLoadingAction
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica el modo de carga de recursos externos.
type: docs
weight: 6761
url: /es/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction enumeración

Especifica el modo de carga de recursos externos.

```cpp
enum class ResourceLoadingAction
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) cargará el recurso externo como de costumbre. |
| Skip | 1 | [Aspose.Slides](../) omitirá la carga del recurso externo. Sólo el enlace sin datos se almacenará para una imagen. |
| UserProvided | 2 | [Aspose.Slides](../) usará la matriz de bytes proporcionada por el usuario en [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) como datos de imagen. |

## Ver también

* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)