---
title: Read()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee un solo carácter del flujo.
type: docs
weight: 40
url: /es/system.io/textreader/read/
---
## TextReader::Read() método

Lee un solo carácter del flujo.

```cpp
virtual int System::IO::TextReader::Read()
```

### Valor devuelto

Carácter leído codificado en UTF-16; si el carácter leído está representado por dos puntos de código en la codificación UTF-16, solo se devuelve el sustituto alto.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) método

Lee la cantidad especificada de caracteres del flujo y los escribe en la matriz de caracteres especificada, comenzando en la posición indicada.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | La matriz de caracteres UTF-16 donde se escribirán los caracteres leídos del flujo |
| index | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres a leer del flujo |

### Valor devuelto

El número de caracteres leídos del flujo

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [TextReader](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)