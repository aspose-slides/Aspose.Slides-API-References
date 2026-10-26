---
title: WriteDocType()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, schrijft het de DOCTYPE-declaratie met de opgegeven naam en optionele attributen.
type: docs
weight: 79
url: /nl/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) methode

Wanneer overschreven in een afgeleide klasse, schrijft het de DOCTYPE-declaratie met de opgegeven naam en optionele attributen.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De naam van de DOCTYPE. Deze mag niet leeg zijn. |
| pubid | const [String](../../../system/string/)\& | Als niet-null schrijft het ook PUBLIC \"pubid\" \"sysid\" waarbij **pubid** en **sysid** worden vervangen door de waarde van de gegeven argumenten. |
| sysid | const [String](../../../system/string/)\& | Als **pubid** **nullptr** is en **sysid** niet-null is, schrijft het SYSTEM \"sysid\" waarbij **sysid** wordt vervangen door de waarde van dit argument. |
| subset | const [String](../../../system/string/)\& | Als niet-null, schrijft het [subset] waarbij subset wordt vervangen door de waarde van dit argument. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)