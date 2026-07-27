---
title: UnknownIsNull()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si un objeto de tipo desconocido es nullptr. Sobrecarga para tipos no escalares.
type: docs
weight: 144
url: /es/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) método

Comprueba si un objeto de tipo desconocido es nullptr. Sobrecarga para tipos no escalares.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | [Object](../../object/) para comprobar. |

### Valor de retorno

Verdadero si 'obj == nullptr' es verdadero, falso en caso contrario.

## ObjectExt::UnknownIsNull(T) método

Comprueba si un objeto de tipo desconocido es nullptr. Sobrecarga para tipos escalares.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | [Object](../../object/) para comprobar. |

### Valor de retorno

Siempre devuelve falso.

## Ver también

* Clase [ObjectExt](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)