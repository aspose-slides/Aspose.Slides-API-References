---
title: GetAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de waarde van het attribuut met de opgegeven naam.
type: docs
weight: 209
url: /nl/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) methode

Retourneert de waarde van het attribuut met de opgegeven naam.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam van het attribuut dat opgehaald moet worden. Dit is een gekwalificeerde naam. Het wordt vergeleken met de **get_Name** waarde van het overeenkomende knooppunt. |

### Retourwaarde

De waarde van het opgegeven attribuut. Een lege tekenreeks wordt geretourneerd als een overeenkomstig attribuut niet wordt gevonden of als het attribuut geen opgegeven of standaardwaarde heeft.

## XmlElement::GetAttribute(String, String) methode

Retourneert de waarde van het attribuut met de opgegeven lokale naam en namespace-URI.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut dat opgehaald moet worden. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut dat opgehaald moet worden. |

### Retourwaarde

De waarde van het opgegeven attribuut. Een lege tekenreeks wordt geretourneerd als een overeenkomstig attribuut niet wordt gevonden of als het attribuut geen opgegeven of standaardwaarde heeft.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)