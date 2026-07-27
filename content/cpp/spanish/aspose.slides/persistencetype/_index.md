---
title: PersistenceType
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica el método utilizado para almacenar las propiedades del control ActiveX.
type: docs
weight: 6189
url: /es/aspose.slides/persistencetype/
---
## PersistenceType enum

Especifica el método utilizado para almacenar las propiedades del control ActiveX.

```cpp
enum class PersistenceType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NotDefined | -1 | Id de persistencia no especificado. |
| PersistPropertyBag | 0 | Especifica que el control ActiveX se persiste utilizando property-bag-based persistence. La property-bag-based persistence almacena un control ActiveX mediante una colección de pares nombre y valor que especifican los datos persistidos por el control ActiveX. |
| PersistStream | 1 | Especifica que el control ActiveX se persiste utilizando una persistencia basada en stream que no soporta la inicialización del control ActiveX a un estado predeterminado. |
| PersistStreamInit | 2 | Especifica que el control ActiveX se persiste utilizando una persistencia basada en stream que soporta la inicialización del control ActiveX a un estado predeterminado. |
| PersistStorage | 3 | Especifica que el control ActiveX se persiste utilizando una persistencia basada en storage. |

## Ver también

* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)