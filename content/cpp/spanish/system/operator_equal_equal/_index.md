---
title: operator==()
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 2042
url: /es/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) función




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) función




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) función




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) función


Determina si el objeto [Nullable](../nullable/) especificado representa un valor que es igual a null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | std::nullptr_t | Una referencia constante a un objeto [Nullable](../nullable/) para probar |

### Valor devuelto

True si el objeto especificado representa un valor null, false en caso contrario

## System::operator==(const T1\&, const Nullable\<T2\>\&) función


Determina si el valor especificado es igual al valor representado por el objeto [Nullable](../nullable/) especificado aplicando [operator==()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del primer valor comparando |
| T2 | El tipo subyacente del objeto [Nullable](../nullable/) que representa el segundo valor comparando |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| some | const T1\& | Una referencia constante al valor que se usará como primer comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Una referencia constante al objeto [Nullable](../nullable/) cuyo valor representado se usará como segundo comparando |

### Valor devuelto

True si los comparandos son iguales, false en caso contrario

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) función


Compara por igualdad dos punteros inteligentes.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado por el primer puntero. |
| Y | Tipo del objeto apuntado por el segundo puntero. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Primer puntero a comparar. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Segundo puntero a comparar. |

### Valor devuelto

True si los punteros coinciden, false en caso contrario.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) función


Comprueba si el puntero inteligente es null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado por el puntero. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | std::nullptr_t | Puntero a comprobar. |

### Valor devuelto

True si el puntero es null, false en caso contrario.

## System::operator==(const SmartPtr\<X\>\&, const Y *) función


Comparación de igualdad entre puntero inteligente y puntero simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del puntero inteligente. |
| Y | Tipo del puntero simple. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Puntero inteligente a comparar (izquierda). |
| y | const Y * | Puntero simple a comparar (derecha). |

### Valor devuelto

True si los punteros coinciden, false en caso contrario.

## System::operator==(const X *, const SmartPtr\<Y\>\&) función


Comparación de igualdad entre puntero simple (C) y puntero inteligente.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del puntero simple. |
| Y | Tipo del puntero inteligente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const X * | Puntero simple a comparar (derecha). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Puntero inteligente a comparar (izquierda). |

### Valor devuelto

True si los punteros coinciden, false en caso contrario.

## System::operator==(T const\&, std::nullptr_t) función


Comprueba si un objeto de tipo valor (estructura traducida de C#, etc.) es null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | T const\& | [Object](../object/) a comprobar. |

### Valor devuelto

True si el objeto es null, false en caso contrario.

## System::operator==(std::nullptr_t, T const\&) función


Comprueba si un objeto de tipo valor (estructura traducida de C#, etc.) es null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo valor. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) a comprobar. |

### Valor devuelto

True si el objeto es null, false en caso contrario.

## System::operator==(Chars\&, const String\&) función


Comparación [String](../string/).

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Chars | Tipo literal [String](../string/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | Chars\& | Literal [String](../string/) a comparar. |
| right | const [String](../string/)\& | [String](../string/) a comparar. |

### Valor devuelto

true si las cadenas coinciden, false en caso contrario.

## System::operator==(T\&, const String\&) función


Comparación [String](../string/).

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero [String](../string/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | T\& | Puntero [String](../string/) a comparar. |
| right | const [String](../string/)\& | [String](../string/) a comparar. |

### Valor devuelto

true si las cadenas coinciden, false en caso contrario.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) función


Comparación entre [Object](../object/) y cadena.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) para convertir a cadena y comparar. |
| right | const [String](../string/)\& | [String](../string/) a comparar. |

### Valor devuelto

true si la representación en cadena del objeto es igual a la cadena, false en caso contrario.

## System::operator==(std::nullptr_t, const String\&) función


Comprueba si la cadena es null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) a comprobar. |

### Valor devuelto

true si la cadena es null, false en caso contrario.

## System::operator==(std::nullptr_t, TimeSpan) función




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) función


Determina si los URIs representados por los objetos actual y especificado son iguales.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | El primer objeto [Uri](../uri/) a comparar |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | El segundo objeto [Uri](../uri/) a comparar |

### Valor devuelto

True si los URIs son iguales, false en caso contrario

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Clase [ArraySegment](../arraysegment/)
* Clase [DateTime](../datetime/)
* Clase [DateTimeOffset](../datetimeoffset/)
* Clase [Nullable](../nullable/)
* Clase [SmartPtr](../smartptr/)
* Clase [Object](../object/)
* Clase [String](../string/)
* Clase [TimeSpan](../timespan/)
* Clase [Uri](../uri/)
* Estructura [IsNullable](../isnullable/)
* Espacio de nombres [System](../)
* Library [Aspose.Slides](../../)