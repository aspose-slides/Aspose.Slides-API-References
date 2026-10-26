---
title: WriteDocType()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft de DOCTYPE-declaratie met de opgegeven naam en optionele attributen.
type: docs
weight: 222
url: /nl/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) method

Schrijft de DOCTYPE-declaratie met de opgegeven naam en optionele attributen.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De naam van de DOCTYPE. Dit moet niet leeg zijn. |
| pubid | const [String](../../../system/string/)\& | Indien niet null wordt ook PUBLIC \"pubid\" \"sysid\" geschreven waarbij **pubid** en **sysid** worden vervangen door de waarde van de opgegeven argumenten. |
| sysid | const [String](../../../system/string/)\& | Als **pubid** null is en **sysid** niet null, wordt SYSTEM \"sysid\" geschreven waarbij **sysid** wordt vervangen door de waarde van dit argument. |
| subset | const [String](../../../system/string/)\& | Indien niet null wordt [subset] geschreven waarbij subset wordt vervangen door de waarde van dit argument. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlTextWriter](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)