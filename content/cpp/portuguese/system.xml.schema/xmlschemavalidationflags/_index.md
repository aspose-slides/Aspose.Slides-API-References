---
title: XmlSchemaValidationFlags
second_title: Referência da API Aspose.Slides para C++
description: Especifica opções de validação de esquema usadas pelas classes XmlSchemaValidator e XmlReader.
type: docs
weight: 1054
url: /pt/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Especifica as opções de validação de esquema usadas pelas classes [XmlSchemaValidator](../xmlschemavalidator/) e [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Não processa restrições de identidade, esquemas embutidos, dicas de localização de esquema ou reporta avisos de validação de esquema. |
| ProcessInlineSchema | 1 | Processa esquemas embutidos encontrados durante a validação. |
| ProcessSchemaLocation | 2 | Processa dicas de localização de esquema (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) encontradas durante a validação. |
| ReportValidationWarnings | 4 | Reporta avisos de validação de esquema encontrados durante a validação. |
| ProcessIdentityConstraints | 8 | Processa restrições de identidade (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) encontradas durante a validação. |
| AllowXmlAttributes | 16 | Permite atributos xml:* mesmo que não estejam definidos no esquema. Os atributos serão validados com base no seu tipo de dado. |

## Veja Também

* Namespace [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)