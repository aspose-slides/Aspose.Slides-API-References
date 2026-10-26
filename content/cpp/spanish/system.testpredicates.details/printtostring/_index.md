---
title: PrintToString()
second_title: Referencia de API de Aspose.Slides para C++
description: Imprime el objeto a una cadena seleccionando la función de serializador adecuada.
type: docs
weight: 1
url: /es/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) función

Imprime el objeto a una cadena seleccionando la función de serializador adecuada.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |

### Valor devuelto

[String](../../system/string/) representaciones del objeto pasado.

## System::TestPredicates::Details::PrintToString(const T\&) función

Imprime contenedores estilo ICollection a una cadena imprimiendo sus elementos (no más de 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) para imprimir. |

### Valor devuelto

Representaciones de cadena conjuntas de los elementos contenidos.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) función

Imprime nullptr a una cadena.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Valor devuelto

\"nullptr\" cadena.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) función

Imprime colecciones [IEnumerable<bool>](../../system.collections.generic/ienumerable/) a una cadena imprimiendo sus elementos (no más de 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) para imprimir. |

### Valor devuelto

Representaciones de cadena conjuntas de los elementos contenidos.

## Véase también

* Clase [IEnumerable](../../system.collections.generic/ienumerable/)
* Estructura [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Espacio de nombres [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)