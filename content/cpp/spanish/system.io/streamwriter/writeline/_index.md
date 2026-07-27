---
title: WriteLine()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe los caracteres terminadores de línea en el flujo.
type: docs
weight: 92
url: /es/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() método


Escribe los caracteres terminadores de línea en el flujo.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) método


Escribe la cadena especificada seguida de los caracteres de terminación de línea en el flujo.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La cadena a escribir |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) método


Escribe la representación en cadena del objeto especificado seguida de los caracteres de terminación de línea en el flujo.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | El objeto a escribir |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) método


Escribe todos los caracteres del arreglo especificado seguido de los caracteres de terminación de línea en el flujo.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El arreglo que contiene los caracteres a escribir |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método


Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado seguido de los caracteres de terminación de línea en el flujo.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El arreglo que contiene los caracteres a escribir |
| index | **int32_t** | Un índice basado en cero del elemento en **buffer** donde comienza el subrango a escribir |
| count | **int32_t** | El número de caracteres en el subrango a escribir; -1 indica que el subrango termina donde finaliza el arreglo **buffer** |

## StreamWriter::WriteLine(const char_t *) método


Escribe la cadena C especificada seguida de los caracteres de terminación de línea en el flujo.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const char_t * | La cadena C a escribir |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) método


Escribe la representación en cadena del objeto especificado seguida de los caracteres de terminación de línea en el flujo.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | El objeto a escribir |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [StreamWriter](../)
* Clase [String](../../../system/string/)
* Clase [Object](../../../system/object/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)