---
title: XmlSchemaValidationFlags
second_title: Riferimento API Aspose.Slides per C++
description: Specifica le opzioni di convalida dello schema utilizzate dalle classi XmlSchemaValidator e XmlReader.
type: docs
weight: 1054
url: /it/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Specifica le opzioni di convalida dello schema utilizzate dalle classi [XmlSchemaValidator](../xmlschemavalidator/) e [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Non elaborare vincoli di identità, schemi in linea, suggerimenti di posizione dello schema o segnalare avvisi di convalida dello schema. |
| ProcessInlineSchema | 1 | Elabora gli schemi in linea incontrati durante la convalida. |
| ProcessSchemaLocation | 2 | Elabora i suggerimenti di posizione dello schema (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) incontrati durante la convalida. |
| ReportValidationWarnings | 4 | Segnala gli avvisi di convalida dello schema incontrati durante la convalida. |
| ProcessIdentityConstraints | 8 | Elabora i vincoli di identità (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) incontrati durante la convalida. |
| AllowXmlAttributes | 16 | Consenti attributi xml:* anche se non sono definiti nello schema. Gli attributi saranno convalidati in base al loro tipo di dati. |

## Vedi anche

* Spazio dei nomi [System::Xml::Schema](../)
* Libreria [Aspose.Slides](../../)