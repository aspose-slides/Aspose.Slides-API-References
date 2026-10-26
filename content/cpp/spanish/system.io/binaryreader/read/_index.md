---
title: Read()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee un solo carácter del flujo de entrada.
type: docs
weight: 66
url: /es/system.io/binaryreader/read/
---
## BinaryReader::Read() método


Lee un solo carácter del flujo de entrada.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### Valor devuelto

Carácter leído codificado con la codificación UTF-16; si el carácter leído está representado por dos codepoints en la codificación UTF-16, solo se devuelve el surrogado alto.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) método


Lee la cantidad especificada de bytes del flujo de entrada y los escribe en la matriz de bytes especificada.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes donde escribir los bytes leídos |
| index | int | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | int | La cantidad de bytes a leer |

### Valor devuelto

El número de bytes leídos

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) método


Lee la cantidad especificada de caracteres del flujo de entrada, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada comenzando en la posición especificada.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | La matriz de caracteres UTF-16 donde escribir los caracteres leídos del flujo de entrada |
| index | int | Un índice basado en 0 en **buffer** en el que comenzar a escribir |
| count | int | La cantidad de caracteres a leer del flujo |

### Valor devuelto

El número de caracteres leídos del flujo de entrada

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BinaryReader](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)