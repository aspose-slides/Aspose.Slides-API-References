---
title: WriteStartElement()
second_title: Aspose.Slides für C++ API Referenz
description: Schreibt das angegebene Start-Tag und verknüpft es mit dem angegebenen Namensraum und Präfix.
type: docs
weight: 235
url: /de/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) Methode

Schreibt das angegebene Start-Tag und verknüpft es mit dem angegebenen Namensraum und Präfix.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Namensraumpräfix des Elements. |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Elements. |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Element zugeordnet werden soll. Wenn dieser Namespace bereits im Gültigkeitsbereich ist und ein zugehöriges Präfix hat, schreibt der Writer dieses Präfix automatisch mit. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)