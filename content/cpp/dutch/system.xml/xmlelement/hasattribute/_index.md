---
title: HasAttribute()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt of het huidige knooppunt een attribuut heeft met de opgegeven naam.
type: docs
weight: 300
url: /nl/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) methode

Bepaalt of het huidige knooppunt een attribuut heeft met de opgegeven naam.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam van het attribuut dat moet worden gevonden. Dit is een gekwalificeerde naam. Het wordt vergeleken met de **get_Name** waarde van het overeenkomende knooppunt. |

### Retourwaarde

**true** als het huidige knooppunt het opgegeven attribuut heeft; anders **false**.

## XmlElement::HasAttribute(String, String) methode

Bepaalt of het huidige knooppunt een attribuut heeft met de opgegeven lokale naam en namespace-URI.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut dat moet worden gevonden. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut dat moet worden gevonden. |

### Retourwaarde

**true** als het huidige knooppunt het opgegeven attribuut heeft; anders **false**.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)