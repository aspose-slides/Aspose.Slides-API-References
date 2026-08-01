---
title: HasFeature()
second_title: Aspose.Slides voor C++ API Referentie
description: Test of de Document Object Model (DOM) implementatie een specifieke functie implementeert.
type: docs
weight: 14
url: /nl/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) methode

Test of de Document [Object](../../../system/object/) Model (DOM) implementatie een specifieke eigenschap implementeert.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | De pakketnaam van de te testen eigenschap. Deze naam is niet hoofdlettergevoelig. |
| strVersion | const [String](../../../system/string/)\& | Dit is het versienummer van de pakketnaam die getest moet worden. Als de versie niet is opgegeven (**nullptr**), zorgt ondersteuning van elke versie van de eigenschap ervoor dat de methode **true** retourneert. |

### Retourwaarde

**true** als de eigenschap is geïmplementeerd in de opgegeven versie; anders **false**.

## Opmerkingen

De volgende tabel toont de combinaties die ervoor zorgen dat **HasFeature** **true** retourneert. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlImplementation](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)