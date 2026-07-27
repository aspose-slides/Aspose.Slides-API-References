---
title: Write()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe la representación en forma de cadena del objeto especificado en el flujo.
type: docs
weight: 105
url: /es/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) método

Escribe la representación en forma de cadena del objeto especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | El objeto a escribir |


## TextWriter::Write(bool) método

Escribe la representación en forma de cadena del valor booleano especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **bool** | El valor a escribir |


## TextWriter::Write(char_t) método

Escribe el carácter especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | El valor a escribir |


## TextWriter::Write(Decimal) método

Escribe la representación en forma de cadena del objeto [Decimal](../../../system/decimal/) especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | El objeto a escribir |


## TextWriter::Write(double) método

Escribe la representación en forma de cadena del valor de punto flotante de doble precisión especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | El valor a escribir |


## TextWriter::Write(int) método

Escribe la representación en forma de cadena del valor entero de 32 bits especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | El valor a escribir |


## TextWriter::Write(int64_t) método

Escribe la representación en forma de cadena del valor entero de 64 bits especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **int64_t** | El valor a escribir |


## TextWriter::Write(float) método

Escribe la representación en forma de cadena del valor de punto flotante de precisión simple especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | El valor a escribir |


## TextWriter::Write(const String\&) método

Escribe la cadena especificada en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La cadena a escribir |


## TextWriter::Write(uint32_t) método

Escribe la representación en forma de cadena del valor entero sin signo de 32 bits especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint32_t** | El valor a escribir |


## TextWriter::Write(uint64_t) método

Escribe la representación en forma de cadena del valor entero sin signo de 64 bits especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint64_t** | El valor a escribir |


## TextWriter::Write(const ArrayPtr\<char_t\>\&) método

Escribe todos los caracteres del array especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El array que contiene los caracteres a escribir |


## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de caracteres UTF-16 del array de caracteres especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El array que contiene los caracteres a escribir |
| index | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de caracteres en el subrango a escribir; -1 indica que el subrango termina donde finaliza el array **buffer** |


## TextWriter::Write(const char_t *) método

Escribe la cadena C especificada en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La cadena C a escribir |


## TextWriter::Write(const TypeInfo\&) método

Escribe la representación en forma de cadena del objeto [TypeInfo](../../../system/typeinfo/) especificado en el flujo.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | El objeto a escribir |


## TextWriter::Write(const String\&, const TArgs\&...) método

Escribe los valores especificados formateados según el formato especificado en el flujo.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TArgs | La lista de tipos de valores a escribir |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | El formato de cadena |
| args | const TArgs\&... | Los valores a escribir |


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Object](../../../system/object/)
* Clase [TextWriter](../)
* Clase [Decimal](../../../system/decimal/)
* Clase [String](../../../system/string/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)