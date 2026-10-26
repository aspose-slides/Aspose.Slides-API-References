---
title: WriteDocType()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, schreibt sie die DOCTYPE-Deklaration mit dem angegebenen Namen und optionalen Attributen.
type: docs
weight: 79
url: /de/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) Methode

Wenn in einer abgeleiteten Klasse überschrieben, schreibt die Methode die DOCTYPE-Deklaration mit dem angegebenen Namen und optionalen Attributen.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Der Name des DOCTYPE. Dieser darf nicht leer sein. |
| pubid | const [String](../../../system/string/)\& | Falls nicht null, schreibt es außerdem PUBLIC \"pubid\" \"sysid\", wobei **pubid** und **sysid** durch die Werte der übergebenen Argumente ersetzt werden. |
| sysid | const [String](../../../system/string/)\& | Wenn **pubid** **nullptr** ist und **sysid** nicht null ist, schreibt es SYSTEM \"sysid\", wobei **sysid** durch den Wert dieses Arguments ersetzt wird. |
| subset | const [String](../../../system/string/)\& | Falls nicht null, schreibt es [subset], wobei subset durch den Wert dieses Arguments ersetzt wird. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)