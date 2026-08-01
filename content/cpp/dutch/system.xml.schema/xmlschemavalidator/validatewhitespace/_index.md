---
title: ValidateWhitespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Valideert of de witruimte in de opgegeven string is toegestaan in de huidige elementcontext, en verzamelt de witruimte voor validatie als het huidige element eenvoudige inhoud heeft.
type: docs
weight: 196
url: /nl/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) methode


Valideert of de witruimte in de **string** die is opgegeven is toegestaan in de huidige elementcontext, en verzamelt de witruimte voor validatie als het huidige element eenvoudige inhoud heeft.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Een witruimte **string** om te valideren in de huidige elementcontext. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) methode


Valideert of de witruimte die wordt geretourneerd door het opgegeven XmlValueGetter-object is toegestaan in de huidige elementcontext, en verzamelt de witruimte voor validatie als het huidige element eenvoudige inhoud heeft.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Een XmlValueGetter-callback die wordt gebruikt om de witruimte-waarde door te geven als een type dat compatibel is met het XML [Schema](../../) Definition Language (XSD)-type van het attribuut. |

## Zie ook

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)