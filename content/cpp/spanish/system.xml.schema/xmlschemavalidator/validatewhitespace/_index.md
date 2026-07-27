---
title: ValidateWhitespace()
second_title: Referencia de API de Aspose.Slides para C++
description: Valida si el espacio en blanco en la cadena especificada está permitido en el contexto del elemento actual y acumula el espacio en blanco para la validación si el elemento actual tiene contenido simple.
type: docs
weight: 196
url: /es/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) method

Valida si el espacio en blanco en la **cadena** especificada está permitido en el contexto del elemento actual y acumula el espacio en blanco para la validación si el elemento actual tiene contenido simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Una **cadena** de espacio en blanco para validar en el contexto del elemento actual. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) method

Valida si el espacio en blanco devuelto por el objeto XmlValueGetter especificado está permitido en el contexto del elemento actual y acumula el espacio en blanco para la validación si el elemento actual tiene contenido simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Una devolución de llamada XmlValueGetter utilizada para pasar el valor del espacio en blanco como un tipo compatible con el lenguaje de definición XML [Schema](../../) (XSD) del atributo. |

## Ver también

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaValidator](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)