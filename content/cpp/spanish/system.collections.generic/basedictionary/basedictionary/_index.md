---
title: BaseDictionary()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una estructura de datos vacía.
type: docs
weight: 14
url: /es/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() constructor

Crea una estructura de datos vacía.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) constructor

Constructor de reenvío para pasar argumentos al constructor del mapa subyacente.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Tipos de argumentos para reenviar al map. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | int | Argumentos para reenviar al mapa subyacente. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) constructor

Constructor de copia.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Tipos de argumentos del constructor del map. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) para copiar datos de. |
| args | const Args\&... | Argumentos para reenviar al constructor del mapa subyacente. |

## BaseDictionary::BaseDictionary(BaseType *) constructor

Constructor de copia.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) para copiar datos de. |

## Ver también

* Typedef [BaseType](../basetype/)
* Clase [BaseDictionary](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)