---
title: get_Encoding()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el nivel de codificación del documento XML.
type: docs
weight: 14
url: /es/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() método

Devuelve el nivel de codificación del documento XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Valor devuelto

El nombre válido de la codificación de caracteres.

## Observaciones

Los nombres de codificación de caracteres más comúnmente compatibles con XML son los siguientes:

| Categoría | Nombres de codificación |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (donde "n" es un dígito del 1 al 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Este valor es opcional. Si no se establece un valor, este método devuelve [String::Empty](../../../system/string/empty/). Si no se incluye un atributo de codificación, se asume la codificación UTF-8 cuando el documento se escribe o se guarda.

## Véase también

* Clase [String](../../../system/string/)
* Clase [XmlDeclaration](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)