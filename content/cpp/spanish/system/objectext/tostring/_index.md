---
title: ToString()
second_title: Referencia de API de Aspose.Slides para C++
description: Sustitución del método ToString de C# para trabajar con cualquier tipo C++.
type: docs
weight: 27
url: /es/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Nullable](../../nullable/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objeto a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(const T\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) valor a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(const T\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero inteligente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) valor a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(T\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero inteligente o [ExceptionWrapper](../../exceptionwrapper/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\& | Puntero inteligente o [ExceptionWrapper](../../exceptionwrapper/) a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(T\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo escalar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\& | Valor escalar a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(T\&&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo escalar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\&& | Valor escalar a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(T\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de estructura. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\& | Valor de estructura a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(const T\&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de estructura. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | Valor de estructura a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## ObjectExt::ToString(T\&&) método

Sustitución del método ToString de C# para trabajar con cualquier tipo C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo escalar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T\&& | Valor escalar a convertir a cadena. |

### Valor devuelto

[String](../../string/) representación de **obj**.

## Ver también

* Clase [String](../../string/)
* Clase [ObjectExt](../)
* Clase [Nullable](../../nullable/)
* Estructura [IsSmartPtr](../../issmartptr/)
* Estructura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)