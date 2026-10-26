---
title: WriteProcessingInstruction()
second_title: Aspose.Slides voor C++ API-referentie
description: "Wanneer overschreven in een afgeleide klasse, schrijft het een verwerkingsinstructie met een spatie tussen de naam en de tekst als volgt: <?name text?>."
type: docs
weight: 196
url: /nl/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) methode

Wanneer overschreven in een afgeleide klasse, schrijft het een verwerkingsinstructie met een spatie tussen de naam en de tekst als volgt: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam van de verwerkingsinstructie. |
| text | [String](../../../system/string/) | De tekst die moet worden opgenomen in de verwerkingsinstructie. |
## Opmerkingen

Deze methode wordt gebruikt om een XML-declaratie te maken nadat [XmlWriter::WriteStartDocument](../writestartdocument/) al is aangeroepen. 
## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)