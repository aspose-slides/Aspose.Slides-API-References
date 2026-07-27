---
title: Append()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega un carácter al constructor.
type: docs
weight: 118
url: /es/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) método


Agrega un carácter al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Valor de carácter. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(char_t, int) método


Agrega caracteres al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | char_t | Valor de carácter. |
| count | int | Cuántas veces repetir el carácter insertado. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) método


Agrega una matriz de caracteres al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caracteres a agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) método


Agrega una porción de la matriz de caracteres al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caracteres a agregar. |
| startIndex | int | Índice inicial de la porción. |
| charCount | int | Longitud de la porción. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(const String\&) método


Agrega una cadena al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) para agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(const String\&, int, int) método


Agrega una porción de cadena al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) para agregar. |
| startIndex | int | Índice inicial de la porción. |
| charCount | int | Longitud de la porción. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(const SharedPtr\<T\>\&) método


Agrega la representación en cadena del objeto al constructor.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../../system/object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) para serializar y agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) método


Agrega el contenido del constructor al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Constructor del que agregar contenido. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(float) método


Agrega un valor de punto flotante al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | **float** | Valor para serializar y agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(double) método


Agrega un valor de punto flotante al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| df | **double** | Valor para serializar y agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(int) método


Agrega un valor entero al constructor.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | int | Valor para serializar y agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(T) método


Agrega un valor aritmético al constructor.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo aritmético. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | Valor para serializar y agregar. |

### Valor de retorno

Este puntero.

## StringBuilder::Append(E) método


Agrega la representación en cadena del valor de enumeración al constructor.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| E | [Enum](../../../system/enum/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| e | E | Valor para serializar y agregar. |

### Valor de retorno

Este puntero.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)