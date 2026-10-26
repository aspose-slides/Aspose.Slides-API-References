---
title: UnboxToNullable()
second_title: Referencia de la API de Aspose.Slides para C++
description: Desempaqueta el objeto a un tipo anulable.
type: docs
weight: 79
url: /es/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) método


Desempaqueta el objeto a un tipo anulable.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de destino. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempaquetar. |
| safe | **bool** | Si true, devuelve nullptr en caso de error, de lo contrario lanza InvalidCastException. |

### Valor devuelto

Valor anulable desempaquetado (puede ser null).

## Ver también

* Clase [Nullable](../../nullable/)
* Clase [SmartPtr](../../smartptr/)
* Clase [Object](../../object/)
* Clase [ObjectExt](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)