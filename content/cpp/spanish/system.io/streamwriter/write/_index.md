---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe el carácter especificado en el flujo.
type: docs
weight: 79
url: /es/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) método

Escribe el carácter especificado en el flujo.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | El carácter a escribir |

## StreamWriter::Write(const String\&) método

Escribe la cadena especificada en el flujo.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La cadena a escribir |

## StreamWriter::Write(const SharedPtr\<Object\>\&) método

Escribe la representación en cadena del objeto especificado en el flujo.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | El objeto a escribir |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) método

Escribe todos los caracteres del arreglo especificado en el flujo.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El arreglo que contiene los caracteres a escribir |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado en el flujo.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El arreglo que contiene los caracteres a escribir |
| index | **int32_t** | Un índice basado en 0 del elemento en **buffer** donde comienza el subrango a escribir |
| count | **int32_t** | El número de caracteres en el subrango a escribir; -1 indica que el subrango termina donde finaliza el arreglo **buffer** |

## StreamWriter::Write(const char_t *) método

Escribe la cadena C especificada en el flujo.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const char_t * | La cadena C a escribir |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) método

Escribe la representación en cadena del objeto especificado en el flujo.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
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
* Biblioteca [Aspose.Slides](../../../)