---
title: ValidationType
second_title: Aspose.Slides for C++ API Referentie
description: Specificeert het type validatie dat moet worden uitgevoerd.
type: docs
weight: 729
url: /nl/system.xml/validationtype/
---
## ValidationType enum

Specificeert het type validatie dat moet worden uitgevoerd.

```cpp
enum class ValidationType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Er wordt geen validatie uitgevoerd, en er worden geen validatiefouten gegenereerd. Deze instelling maakt een XML 1.0-conforme niet-validerende parser aan. |
| Auto | 1 | Valideert als DTD- of schema-informatie wordt gevonden. |
| DTD | 2 | Valideert volgens de DTD. |
| XDR | 3 | Valideert volgens XML-Data Reduced (XDR) schema’s, inclusief inline XDR-schema’s. XDR-schema’s worden herkend met het **x-schema** namespace-voorvoegsel of de [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/)-waarde. |
| Schema | 4 | Valideert volgens XML [Schema](../../system.xml.schema/) definities (XSD) schema’s, inclusief inline XML-schema’s. XML-schema’s worden gekoppeld aan namespace-URI’s door het **schemaLocation**-attribuut te gebruiken of de aangeleverde **Schemas**. |

## Zie ook

* Naamruimte [System::Xml](../)
* Bibliotheek [Aspose.Slides](../../)