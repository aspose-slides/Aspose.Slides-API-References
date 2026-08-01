---
title: XmlSeverityType
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de ernst van het validatie-evenement weer.
type: docs
weight: 1080
url: /nl/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Geeft de ernst van het validatie-evenement weer.

```cpp
enum class XmlSeverityType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Error | 0 | Geeft aan dat er een validatiefout is opgetreden tijdens het valideren van het exemplaar-document. Dit geldt voor documenttype-definities (DTDs) en XML [Schema](../) definitietaal (XSD) schema's. De World Wide [Web](../../system.web/) Consortium (W3C) geldigheids-constraints worden beschouwd als fouten. Als er geen validatie-event-handler is gemaakt, veroorzaken fouten een uitzondering. |
| Warning | 1 | Geeft aan dat er een validatie-event is opgetreden dat geen fout is. Een waarschuwing wordt doorgaans uitgegeven wanneer er geen DTD is, of XML [Schema](../) om een bepaald element of attribuut tegen te valideren. In tegenstelling tot fouten, veroorzaken waarschuwingen geen uitzondering als er geen validatie-event-handler is. |

## Zie ook

* Naamruimte [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)