---
title: ToByteArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena o subcadena a una matriz de bytes.
type: docs
weight: 508
url: /es/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const método

Convierte una cadena o subcadena a una matriz de bytes.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **int32_t** | Índice de inicio de la subcadena. |
| length | **int32_t** | Longitud de la subcadena. |
| LE | **bool** | Si es true, codifica los caracteres usando little endianness; de lo contrario, usa big endianness. |

### Valor devuelto

[Array](../../array/) que contiene bytes que representan los caracteres de la cadena.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)