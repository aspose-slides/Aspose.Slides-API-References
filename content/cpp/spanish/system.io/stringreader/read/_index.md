---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee un solo carácter del flujo.
type: docs
weight: 40
url: /es/system.io/stringreader/read/
---
## StringReader::Read() método

Lee un solo carácter del flujo.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Valor devuelto

Un carácter leído o -1 si no se ha leído ningún carácter

## StringReader::Read(ArrayPtr\<char_t\>, int, int) método

Lee la cantidad especificada de caracteres del flujo al array de caracteres especificado comenzando en la posición especificada.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | El array de caracteres donde escribir los caracteres leídos del flujo |
| index | int | Un índice basado en 0 en **buffer** donde comenzar a escribir |
| count | int | El número de caracteres que se leerán del flujo |

### Valor devuelto

El número de caracteres leídos del flujo

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [StringReader](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)