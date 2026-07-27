---
title: ValidationType
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica el tipo de validación a realizar.
type: docs
weight: 729
url: /es/system.xml/validationtype/
---
## ValidationType enum

Especifica el tipo de validación a realizar.

```cpp
enum class ValidationType
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No se realiza ninguna validación, y no se generan errores de validación. Esta configuración crea un analizador no validante compatible con XML 1.0. |
| Auto | 1 | Valida si se encuentra información DTD o de esquema. |
| DTD | 2 | Valida según el DTD. |
| XDR | 3 | Valida según los esquemas XML-Data Reduced (XDR), incluidos los esquemas XDR en línea. Los esquemas XDR se reconocen mediante el prefijo de espacio de nombres **x-schema** o el valor [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Valida según los esquemas del lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD), incluidos los esquemas XML en línea. Los esquemas XML se asocian a URIs de espacio de nombres ya sea mediante el atributo **schemaLocation** o los **Schemas** proporcionados. |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)