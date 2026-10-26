---
title: Write()
second_title: Referencia API de Aspose.Slides para C++
description: Escribe el carácter especificado en el flujo.
type: docs
weight: 40
url: /es/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) método


Escribe el carácter especificado en el flujo.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char_t | El valor a escribir |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método


Escribe el subrango especificado de caracteres del arreglo de caracteres especificado en el flujo.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El arreglo que contiene los caracteres a escribir |
| index | **int32_t** | Un índice basado en 0 del elemnet en **buffer** donde comienza el subrango a escribir |
| count | **int32_t** | El número de caracteres en el subrango a escribir |

## StringWriter::Write(const String\&) método


Escribe la cadena especificada en el flujo.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La cadena a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [StringWriter](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)