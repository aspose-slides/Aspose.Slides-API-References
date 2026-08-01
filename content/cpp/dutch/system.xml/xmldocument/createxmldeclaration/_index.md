---
title: CreateXmlDeclaration()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een XmlDeclaration knooppunt met de opgegeven waarden.
type: docs
weight: 378
url: /nl/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String&, const String&, const String&) methode

Maakt een [XmlDeclaration](../../xmldeclaration/) knooppunt met de opgegeven waarden.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| version | const [String](../../../system/string/)& | De versie moet \"1.0\" zijn. |
| encoding | const [String](../../../system/string/)& | De waarde van het encoding-attribuut. Dit is de encoding die wordt gebruikt wanneer u de [XmlDocument](../) opslaat naar een bestand of een stream; daarom moet deze worden ingesteld op een string die wordt ondersteund door de [Text::Encoding](../../../system.text/encoding/) class, anders faalt \"XmlDocument::Save(String)\". Als dit **nullptr** of [String::Empty](../../../system/string/empty/) is, schrijft de [XmlDocument::Save](../save/) methode geen encoding-attribuut in de XML-declaratie en wordt daarom de standaardencoding, UTF-8, gebruikt. |
| standalone | const [String](../../../system/string/)& | De waarde moet \"yes\" of \"no\" zijn. Als dit **nullptr** of [String::Empty](../../../system/string/empty/) is, schrijft de [XmlDocument::Save](../save/) methode geen standalone-attribuut in de XML-declaratie. |

### Retourwaarde

Het nieuwe [XmlDeclaration](../../xmldeclaration/) knooppunt.

## Opmerkingen

Opmerking: Als de [XmlDocument](../) wordt opgeslagen naar een TextWriter of een [XmlTextWriter](../../xmltextwriter/), wordt deze encoding-waarde genegeerd. In plaats daarvan wordt de encoding van de TextWriter of de [XmlTextWriter](../../xmltextwriter/) gebruikt. Dit zorgt ervoor dat de uitgevoerde XML kan worden gelezen met de juiste encoding.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlDeclaration](../../xmldeclaration/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)