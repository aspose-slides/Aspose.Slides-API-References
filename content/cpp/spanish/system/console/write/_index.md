---
title: Write()
second_title: Referencia de la API de Aspose.Slides para C++
description: Genera la representación en cadena del objeto especificado en el flujo de salida estándar.
type: docs
weight: 1
url: /es/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) método


Genera la representación en cadena del objeto especificado en el flujo de salida estándar.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo del objeto a generar |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) to output |

## Console::Write(bool) método


Genera la representación en cadena del valor bool en el flujo de salida estándar.

```cpp
static void System::Console::Write(bool value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **bool** | The value to output |

## Console::Write(char_t) método


Genera el carácter especificado en el flujo de salida estándar.

```cpp
static void System::Console::Write(char_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | The value to output |

## Console::Write(const ArrayPtr\<char_t\>\&) método


Genera la representación en cadena del arreglo de caracteres especificado en el flujo de salida estándar.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The array to output |

## Console::Write(const Decimal\&) método


Genera la representación en cadena del valor [Decimal](../../decimal/) en el flujo de salida estándar.

```cpp
static void System::Console::Write(const Decimal &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to output |

## Console::Write(double) método


Genera la representación en cadena del valor de punto flotante de doble precisión en el flujo de salida estándar.

```cpp
static void System::Console::Write(double value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | The value to output |

## Console::Write(float) método


Genera la representación en cadena del valor de punto flotante de precisión simple en el flujo de salida estándar.

```cpp
static void System::Console::Write(float value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | The value to output |

## Console::Write(int32_t) método


Genera la representación en cadena del valor entero de 32 bits en el flujo de salida estándar.

```cpp
static void System::Console::Write(int32_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **int32_t** | The value to output |

## Console::Write(int64_t) método


Genera la representación en cadena del valor entero de 64 bits en el flujo de salida estándar.

```cpp
static void System::Console::Write(int64_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **int64_t** | The value to output |

## Console::Write(const String\&) método


Genera el objeto string especificado en el flujo de salida estándar.

```cpp
static void System::Console::Write(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string object to output |

## Console::Write(const char_t *) método


Genera la c-string especificada en el flujo de salida estándar.

```cpp
static void System::Console::Write(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | The c-string to output |

## Console::Write(const TypeInfo\&) método


Genera la representación en cadena del valor [TypeInfo](../../typeinfo/) en el flujo de salida estándar.

```cpp
static void System::Console::Write(const TypeInfo &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | The value to output |

## Console::Write(uint32_t) método


Genera la representación en cadena del valor entero sin signo de 32 bits en el flujo de salida estándar.

```cpp
static void System::Console::Write(uint32_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint32_t** | The value to output |

## Console::Write(uint64_t) método


Genera la representación en cadena del valor entero sin signo de 64 bits en el flujo de salida estándar.

```cpp
static void System::Console::Write(uint64_t value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint64_t** | The value to output |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método


Genera la representación en cadena del rango especificado del arreglo de caracteres especificado en el flujo de salida estándar.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The character array |
| index | **int32_t** | The index in the array at which the range to output begins |
| count | **int32_t** | The number of elements in the range to output |

## Console::Write(const String\&, Args\&&...) método


Genera la representación en cadena de los argumentos especificados formateados según el formato especificado en el flujo de salida estándar.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| The | types of the values to output |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../string/)\& | The string format |
| args | Args\&&... | The values to output |

## Console::Write(const char *) método




```cpp
static void System::Console::Write(const char *)=delete
```

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)