---
title: CastEnumerableTo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Realiza la conversión explícita de los elementos del objeto enumerable especificado a un tipo diferente.
type: docs
weight: 2965
url: /es/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) función

Realiza la conversión explícita de los elementos del objeto enumerable especificado a un tipo diferente.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se convierten estáticamente los elementos del objeto enumerable |
| From | El tipo del objeto enumerable |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | const From\& | Objeto enumerable que contiene los elementos a convertir |

### Valor devuelto

Un puntero a una nueva colección que contiene elementos del tipo **To** equivalentes a los elementos de **enumerable**

## System::CastEnumerableTo(const From\&) función

Realiza la conversión explícita de los elementos del objeto enumerable especificado a un tipo diferente.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se convierten estáticamente los elementos del objeto enumerable |
| From | El tipo del objeto enumerable |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | const From\& | es heredero de un objeto Enumerable con el método get_Count definido y que contiene los elementos a convertir |

### Valor devuelto

Un puntero a una nueva colección que contiene elementos del tipo **To** equivalentes a los elementos de **enumerable**

## Ver también

* Clase [ListPtr](../../system.collections.generic/listptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)