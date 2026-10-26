---
title: WriteProcessingInstruction()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn in einer abgeleiteten Klasse überschrieben, schreibt es eine Verarbeitungsanweisung mit einem Leerzeichen zwischen Name und Text wie folgt: <?name text?>."
type: docs
weight: 196
url: /de/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) Methode

When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name der Verarbeitungsanweisung. |
| text | [String](../../../system/string/) | Der Text, der in die Verarbeitungsanweisung aufgenommen werden soll. |
## Bemerkungen

Diese Methode wird verwendet, um eine XML-Deklaration zu erstellen, nachdem [XmlWriter::WriteStartDocument](../writestartdocument/) bereits aufgerufen wurde. 
## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)