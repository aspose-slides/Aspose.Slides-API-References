---
title: GetType()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementa la traducción de typeof(). Sobrecarga para punteros inteligentes.
type: docs
weight: 1
url: /es/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) método


Implementa la traducción de typeof(). Sobrecarga para punteros inteligentes.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de objeto puntero. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obtener [TypeInfo](../../typeinfo/). |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la clase final del objeto pasado.

## ObjectType::GetType(const T\&) método


Implementa la traducción de typeof(). Sobrecarga para estructuras.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de estructura. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obtener [TypeInfo](../../typeinfo/). |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la clase final del objeto pasado.

## ObjectType::GetType(const T\&) método


Implementa la traducción de typeof(). Sobrecarga para excepciones.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de excepción. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) para obtener [TypeInfo](../../typeinfo/). |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la clase final del objeto pasado.

## ObjectType::GetType(const T) método


Implementa la traducción de typeof(). Sobrecarga para tipos primitivos.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T | IGNORED |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo del objeto pasado.

## ObjectType::GetType(const T) método


Implementa la traducción de typeof(). Sobrecarga para tipos [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T | IGNORED |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo del objeto pasado.

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para tipos primitivos.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo especificado.

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo especificado.

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para estructuras y punteros.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada.

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada.

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo MutlicastDelegate. |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada.

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para estructuras y punteros.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe la estructura especificada o el tipo apuntado si se llama para [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) método


Implementa la traducción de typeof(). Sobrecarga para tipo cadena.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo primitivo. |

### Valor de retorno

Referencia constante a la estructura [TypeInfo](../../typeinfo/) que describe el tipo [String](../../string/).

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() método


Implementa la traducción de typeof(). Sobrecarga para [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Ver también

* Clase [ObjectType](../)
* Clase [TypeInfo](../../typeinfo/)
* Clase [String](../../string/)
* Estructura [IsSmartPtr](../../issmartptr/)
* Estructura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estructura [IsNullable](../../isnullable/)
* Estructura [IsBoxable](../../isboxable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)