---
title: HexUnescape()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la representación hexadecimal especificada de un carácter a un carácter.
type: docs
weight: 443
url: /es/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) método

Convierte la representación hexadecimal especificada de un carácter a un carácter.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Una cadena que contiene la representación hexadecimal de un carácter |
| index | **int32_t**\& | La posición en **pattern** donde comienza la representación hexadecimal de un carácter |

### Valor devuelto

El carácter representado por la codificación hexadecimal en la posición **index**. Si el carácter en **index** no está codificado en hexadecimal, se devuelve el carácter en **index**. El valor de **index** se incrementa para apuntar al carácter que sigue al devuelto.

## Ver también

* Clase [String](../../string/)
* Clase [Uri](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)