---
title: Box()
second_title: Referencia de la API de Aspose.Slides para C++
description: Encapsula tipos de valor para convertir a Object. Implementación para tipos enum.
type: docs
weight: 40
url: /es/system/objectext/box/
---
## ObjectExt::Box(const T\&) método

Encapsula tipos de valor para convertir a [Object](../../object/). Implementación para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) valor a encapsular. |

### Valor devuelto

Puntero inteligente a objeto que conserva el valor encapsulado.

## ObjectExt::Box(const T\&) método

Encapsula tipos de valor para convertir a [Object](../../object/). Implementación para tipos no enum.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | Valor a encapsular. |

### Valor devuelto

Puntero inteligente a objeto que conserva el valor encapsulado.

## ObjectExt::Box(const T\&) método

Encapsula tipos [Nullable](../../nullable/) para convertir a [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | Valor a encapsular. |

### Valor devuelto

Puntero inteligente a objeto que conserva el valor encapsulado.

## ObjectExt::Box(const String\&) método

Encapsula valores de cadena.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | Valor a encapsular. |

### Valor devuelto

Valor encapsulado o null, si la cadena de origen es null.

## Ver también

* Clase [SmartPtr](../../smartptr/)
* Clase [Object](../../object/)
* Clase [ObjectExt](../)
* Clase [String](../../string/)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)