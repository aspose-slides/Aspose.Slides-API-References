---
title: XmlSchemaValidationFlags
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica las opciones de validación de esquemas utilizadas por las clases XmlSchemaValidator y XmlReader.
type: docs
weight: 1054
url: /es/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Especifica las opciones de validación de esquemas utilizadas por las clases [XmlSchemaValidator](../xmlschemavalidator/) y [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | No procesar restricciones de identidad, esquemas en línea, sugerencias de ubicación de esquema, ni informar advertencias de validación de esquemas. |
| ProcessInlineSchema | 1 | Procesar esquemas en línea encontrados durante la validación. |
| ProcessSchemaLocation | 2 | Procesar sugerencias de ubicación de esquema (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) encontradas durante la validación. |
| ReportValidationWarnings | 4 | Informar advertencias de validación de esquemas encontradas durante la validación. |
| ProcessIdentityConstraints | 8 | Procesar restricciones de identidad (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) encontradas durante la validación. |
| AllowXmlAttributes | 16 | Permitir atributos xml:* incluso si no están definidos en el esquema. Los atributos se validarán según su tipo de datos. |

## Ver también

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)