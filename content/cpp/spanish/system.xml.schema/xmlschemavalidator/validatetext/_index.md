---
title: ValidateText()
second_title: Referencia de API de Aspose.Slides para C++
description: Valida si la cadena de texto especificada está permitida en el contexto del elemento actual y acumula el texto para su validación si el elemento actual tiene contenido simple.
type: docs
weight: 183
url: /es/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) método


Valida si la **cadena** de texto especificada está permitida en el contexto del elemento actual, y acumula el texto para su validación si el elemento actual tiene contenido simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Una **cadena** de texto para validar en el contexto del elemento actual. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) método


Valida si el texto devuelto por el objeto XmlValueGetter especificado está permitido en el contexto del elemento actual, y acumula el texto para su validación si el elemento actual tiene contenido simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Una devolución de llamada XmlValueGetter utilizada para pasar el valor de texto como un tipo compatible con el lenguaje de definición XML [Schema](../../) (XSD) del atributo. |

## Ver también

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaValidator](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)