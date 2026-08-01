---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekenreekswaarde van de XmlQualifiedName.
type: docs
weight: 79
url: /nl/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const methode

Retourneert de tekenreekswaarde van de [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### Retourwaarde

De tekenreekswaarde van de [XmlQualifiedName](../) in het formaat **namespace:localname**. Als het object geen gedefinieerde namespace heeft, retourneert deze methode alleen de lokale naam.

## XmlQualifiedName::ToString(const String\&, const String\&) methode

Retourneert de tekenreekswaarde van de [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De naam van het object. |
| ns | const [String](../../../system/string/)\& | De naamruimte van het object. |

### Retourwaarde

De tekenreekswaarde van de [XmlQualifiedName](../) in het formaat **namespace:localname**. Als het object geen gedefinieerde namespace heeft, retourneert deze methode alleen de lokale naam.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlQualifiedName](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)