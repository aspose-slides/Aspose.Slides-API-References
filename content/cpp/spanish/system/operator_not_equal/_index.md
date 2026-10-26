---
title: operator!=()
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 2055
url: /es/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) función

```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) función

```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) función

```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) función

Determina si el objeto [Nullable](../nullable/) especificado representa un valor que no es igual a nulo.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | std::nullptr_t | Una referencia constante a un objeto [Nullable](../nullable/) para probar |

### Valor devuelto

Verdadero si el objeto especificado representa un valor no nulo, falso en caso contrario

## System::operator!=(const T1\&, const Nullable\<T2\>\&) función

Determina si el valor especificado no es igual al valor representado por el objeto [Nullable](../nullable/) especificado aplicando [operator!=()](./) a estos valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
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

Verdadero si los comparandos no son iguales, de lo contrario falso

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) función

Compara la desigualdad de dos punteros inteligentes.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
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

Falso si los punteros coinciden, verdadero en caso contrario.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) función

Comprueba si el puntero inteligente no es nulo.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del objeto apuntado por el puntero. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Puntero a comprobar. |

### Valor devuelto

Falso si el puntero es nulo, verdadero en caso contrario.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) función

Comprueba si el puntero inteligente no es nulo.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
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

Falso si el puntero es nulo, verdadero en caso contrario.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) función

Comparación de desigualdad entre puntero inteligente y puntero simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del puntero inteligente. |
| Y | Tipo del puntero simple. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | puntero inteligente a comparar (izquierda). |
| y | const Y * | puntero a comparar (derecha). |

### Valor devuelto

Falso si los punteros coinciden, verdadero en caso contrario.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) función

Comparación de igualdad entre puntero inteligente y puntero simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| X | Tipo del puntero simple. |
| Y | Tipo del puntero inteligente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | const X * | puntero a comparar (derecha). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | puntero inteligente a comparar (izquierda). |

### Valor devuelto

Falso si los punteros coinciden, verdadero en caso contrario.

## System::operator!=(Chars\&, const String\&) función

[String](../string/) comparación.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Chars | Tipo literal [String](../string/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | Chars\& | literal [String](../string/) a comparar. |
| right | const [String](../string/)\& | [String](../string/) a comparar. |

### Valor devuelto

Falso si las cadenas coinciden, verdadero en caso contrario.

## System::operator!=(T\&, const String\&) función

[String](../string/) comparación.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de puntero [String](../string/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | T\& | puntero [String](../string/) a comparar. |
| right | const [String](../string/)\& | [String](../string/) a comparar. |

### Valor devuelto

Falso si las cadenas coinciden, verdadero en caso contrario.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) función

[Object](../object/) y comparación de cadena.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) para convertir a cadena y comparar. |
| right | const [String](../string/)\& | [String](../string/) a comparar. |

### Valor devuelto

Falso si la representación en cadena del objeto es igual a la cadena, verdadero en caso contrario.

## System::operator!=(std::nullptr_t, const String\&) función

Comprueba si la cadena es nula.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) a comprobar. |

### Valor devuelto

Falso si la cadena es nula, verdadero en caso contrario.

## System::operator!=(std::nullptr_t, TimeSpan) función

```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) función

Determina si los URIs representados por los objetos actual y especificado no son iguales.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | El primer objeto [Uri](../uri/) a comparar |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | El segundo objeto [Uri](../uri/) a comparar |

### Valor devuelto

Verdadero si los URIs no son iguales, de lo contrario falso

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
* Biblioteca [Aspose.Slides](../../)