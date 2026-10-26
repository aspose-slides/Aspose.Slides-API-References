---
title: ReadBlock()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el número máximo especificado de caracteres del lector de texto actual y escribe los datos en un búfer, comenzando en el índice especificado.
type: docs
weight: 53
url: /es/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) método

Lee el número máximo especificado de caracteres del lector de texto actual y escribe los datos en un búfer, comenzando en el índice especificado.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Un búfer de caracteres para escribir los datos leídos |
| index | int | Un índice basado en 0 en **buffer** para comenzar a escribir |
| count | int | El número máximo de caracteres a leer |

### Valor devuelto

El número real de caracteres leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [TextReader](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)