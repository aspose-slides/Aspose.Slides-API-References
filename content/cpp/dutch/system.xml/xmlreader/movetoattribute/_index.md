---
title: MoveToAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: "Wanneer het wordt overschreven in een afgeleide klasse, beweegt het naar het attribuut met de opgegeven XmlReader::get_Name-waarde."
type: docs
weight: 625
url: /nl/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) methode


Wanneer het wordt overschreven in een afgeleide klasse, beweegt het naar het attribuut met de opgegeven [XmlReader::get_Name](../get_name/)-waarde.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

**true** als het attribuut wordt gevonden; anders **false**. Als **false**, verandert de positie van de lezer niet.

## XmlReader::MoveToAttribute(String, String) methode


Wanneer het wordt overschreven in een afgeleide klasse, beweegt het naar het attribuut met de opgegeven [XmlReader::get_LocalName](../get_localname/)- en [XmlReader::get_NamespaceURI](../get_namespaceuri/)-waarden.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van het attribuut. |
| ns | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

**true** als het attribuut wordt gevonden; anders **false**. Als **false**, verandert de positie van de lezer niet.

## XmlReader::MoveToAttribute(int32_t) methode


Wanneer het wordt overschreven in een afgeleide klasse, beweegt het naar het attribuut met de opgegeven index.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)