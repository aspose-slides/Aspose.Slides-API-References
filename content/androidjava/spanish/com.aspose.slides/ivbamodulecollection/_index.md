---
title: IVbaModuleCollection
second_title: Aspose.Slides para Android vía la referencia de la API Java
description: Representa una colección de módulos de proyecto VBA.
type: docs
url: /es/com.aspose.slides/ivbamodulecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Representa una colección de módulos de proyecto VBA.

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Agrega un nuevo módulo vacío al proyecto VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Elimina la primera aparición de un objeto específico de la colección. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IVbaModule](../../com.aspose.slides/ivbamodule)

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

Agrega un nuevo módulo vacío al proyecto VBA.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre del módulo |

**Devuelve:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Módulo agregado.

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Elimina la primera aparición de un objeto específico de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | El módulo a eliminar de la colección. |