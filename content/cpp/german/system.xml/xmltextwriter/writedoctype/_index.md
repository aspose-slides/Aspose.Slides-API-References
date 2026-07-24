---
title: WriteDocType()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt die DOCTYPE-Deklaration mit dem angegebenen Namen und optionalen Attributen.
type: docs
weight: 222
url: /de/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) Methode

Schreibt die DOCTYPE-Deklaration mit dem angegebenen Namen und optionalen Attributen.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der Name des DOCTYPE. Dieser muss nicht leer sein. |
| pubid | const [String](../../../system/string/)\& | Wenn nicht null, schreibt es zusätzlich PUBLIC \"pubid\" \"sysid\", wobei **pubid** und **sysid** durch die Werte der übergebenen Argumente ersetzt werden. |
| sysid | const [String](../../../system/string/)\& | Wenn **pubid** null ist und **sysid** nicht null ist, schreibt es SYSTEM \"sysid\", wobei **sysid** durch den Wert dieses Arguments ersetzt wird. |
| subset | const [String](../../../system/string/)\& | Wenn nicht null, schreibt es [subset], wobei subset durch den Wert dieses Arguments ersetzt wird. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)