---
title: PeekChar()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee un solo carácter del flujo de entrada sin cambiar el cursor de lectura del flujo.
type: docs
weight: 53
url: /es/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() método


Lee un solo carácter del flujo de entrada sin cambiar el cursor de lectura del flujo.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```


### Valor de retorno

Carácter leído codificado con codificación UTF-16; si el carácter leído está representado por dos puntos de código en la codificación UTF-16, solo se devuelve el surrogate alto; si no se leyó ningún carácter, se devuelve -1

## Ver también

* Clase [BinaryReader](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)