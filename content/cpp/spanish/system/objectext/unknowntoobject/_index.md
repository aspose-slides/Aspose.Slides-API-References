---
title: UnknownToObject()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte un tipo desconocido a Object, manejando tanto situaciones de tipo puntero inteligente como de tipo valor.
type: docs
weight: 118
url: /es/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) método

Convierte un tipo desconocido a [Object](../../object/), manejando tanto situaciones de puntero inteligente como de tipo valor.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que convertir a [Object](../../object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | [Object](../../object/) a convertir. |

### Valor devuelto

Puntero inteligente a [Object](../../object/) que es un puntero convertido o un valor encapsulado.

## ObjectExt::UnknownToObject(const T\&) método

Convierte un tipo desconocido a [Object](../../object/), manejando tanto situaciones de puntero inteligente como de tipo valor.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que convertir a [Object](../../object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a convertir. |

### Valor devuelto

Puntero inteligente a [Object](../../object/) que es un puntero convertido o un valor encapsulado.

## Ver también

* Clase [SmartPtr](../../smartptr/)
* Clase [Object](../../object/)
* Clase [ObjectExt](../)
* Estructura [IsSmartPtr](../../issmartptr/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)