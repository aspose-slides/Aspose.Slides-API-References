---
title: Read()
second_title: Referencia de la API de Aspose.Slides for C++
description: Lee un solo carácter del flujo.
type: docs
weight: 40
url: /es/system.io/streamreader/read/
---
## StreamReader::Read() método

Lee un solo carácter del flujo.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### Valor devuelto

Carácter leído codificado con codificación UTF-16; si el carácter leído está representado por dos puntos de código en la codificación UTF-16 entonces solo se devuelve el sustituto alto.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) método

Lee la cantidad especificada de caracteres del flujo, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada comenzando en la posición especificada.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | La matriz de caracteres UTF-16 donde escribir los caracteres leídos del flujo |
| index | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres a leer del flujo |

### Valor devuelto

El número de caracteres leídos del flujo

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [StreamReader](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)