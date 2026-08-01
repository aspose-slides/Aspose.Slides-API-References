---
title: ReadToFollowing()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest totdat een element met de opgegeven gekwalificeerde naam wordt gevonden.
type: docs
weight: 898
url: /nl/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) methode

Leest totdat een element met de opgegeven gekwalificeerde naam wordt gevonden.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het element. |

### Retourwaarde

**true** als een overeenkomend element wordt gevonden; anders **false** en [XmlReader](../) bevindt zich in een einde-van-bestand-status.

## XmlReader::ReadToFollowing(String, String) methode

Leest totdat een element met de opgegeven lokale naam en namespace-URI wordt gevonden.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het element. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het element. |

### Retourwaarde

**true** als een overeenkomend element wordt gevonden; anders **false** en [XmlReader](../) bevindt zich in een einde-van-bestand-status.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)