---
title: IsDefined()
second_title: Referencia de API de Aspose.Slides para C++
description: NO IMPLEMENTADO. Indica si uno o más atributos del tipo especificado o de sus tipos derivados se aplican a este miembro.
type: docs
weight: 157
url: /es/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const método

NO IMPLEMENTADO. Indica si uno o más atributos del tipo especificado o de sus tipos derivados se aplican a este miembro.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | El tipo de atributo personalizado a buscar. La búsqueda incluye tipos derivados. |
| inherit | **bool** | true para buscar en la cadena de herencia de este miembro los atributos; de lo contrario, false. Este parámetro se ignora para propiedades y eventos. |

### Valor de retorno

true si una o más instancias de attributeType o cualquiera de sus tipos derivados se aplica a este miembro; de lo contrario, false.

## Ver también

* Clase [TypeInfo](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)