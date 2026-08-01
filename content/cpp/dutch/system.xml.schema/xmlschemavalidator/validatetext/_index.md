---
title: ValidateText()
second_title: Aspose.Slides voor C++ API-referentie
description: Valideert of de opgegeven tekenreeks is toegestaan in de huidige elementcontext, en verzamelt de tekst voor validatie als het huidige element eenvoudige inhoud heeft.
type: docs
weight: 183
url: /nl/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) methode

Valideert of de opgegeven tekst **tekenreeks** is toegestaan in de huidige elementcontext, en verzamelt de tekst voor validatie als het huidige element eenvoudige inhoud heeft.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Een tekst **tekenreeks** om te valideren in de huidige elementcontext. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) methode

Valideert of de tekst die wordt geretourneerd door het opgegeven XmlValueGetter-object is toegestaan in de huidige elementcontext, en verzamelt de tekst voor validatie als het huidige element eenvoudige inhoud heeft.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Een XmlValueGetter-callback die wordt gebruikt om de tekstwaarde door te geven als een type dat compatibel is met het XML [Schema](../../) Definition Language (XSD)-type van het attribuut. |

## Zie ook

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSchemaValidator](../)
* Naamruimte [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)