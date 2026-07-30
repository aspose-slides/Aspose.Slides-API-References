---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje možnosti ověřování schématu používané třídami XmlSchemaValidator a XmlReader.
type: docs
weight: 1054
url: /cs/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Určuje možnosti ověřování schématu používané třídami [XmlSchemaValidator](../xmlschemavalidator/) a [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Nezpracovávejte identitní omezení, vložená schémata, nápovědy umístění schématu ani nehlášejte varování při ověřování schématu. |
| ProcessInlineSchema | 1 | Zpracovat vložená schémata nalezená během ověřování. |
| ProcessSchemaLocation | 2 | Zpracovat nápovědy umístění schématu (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) nalezené během ověřování. |
| ReportValidationWarnings | 4 | Hlásit varování při ověřování schématu nalezená během ověřování. |
| ProcessIdentityConstraints | 8 | Zpracovat identitní omezení (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) nalezená během ověřování. |
| AllowXmlAttributes | 16 | Povolit atributy xml:* i když nejsou ve schématu definovány. Atributy budou ověřeny na základě jejich datového typu. |

## Viz také

* Jmenný prostor [System::Xml::Schema](../)
* Knihovna [Aspose.Slides](../../)