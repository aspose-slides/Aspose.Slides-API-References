---
title: WriteStartElement()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie das angegebene Start-Tag und verknüpft es mit dem angegebenen Namespace.
type: docs
weight: 92
url: /de/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie das angegebene Start-Tag und verknüpft es mit dem angegebenen Namespace.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Elements. |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Element zugeordnet werden soll. Wenn dieser Namespace bereits im Geltungsbereich ist und ein zugehöriges Präfix hat, schreibt der Writer dieses Präfix ebenfalls automatisch. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie das angegebene Start-Tag und verknüpft es mit dem angegebenen Namespace und Präfix.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Das Namespace-Präfix des Elements. |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Elements. |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI, der dem Element zugeordnet werden soll. |

## XmlWriter::WriteStartElement(const String\&) Methode

Wenn sie in einer abgeleiteten Klasse überschrieben wird, schreibt sie ein Start-Tag mit dem angegebenen lokalen Namen.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Elements. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)