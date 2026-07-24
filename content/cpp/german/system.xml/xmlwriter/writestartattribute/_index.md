---
title: WriteStartAttribute()
second_title: Aspose.Slides für C++ API Referenz
description: Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen und dem Namespace-URI.
type: docs
weight: 144
url: /de/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) Methode

Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen und dem Namespace-URI.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Attributs. |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI des Attributs. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) Methode

Wenn in einer abgeleiteten Klasse überschrieben, schreibt es den Beginn eines Attributs mit dem angegebenen Präfix, lokalen Namen und Namespace-URI.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Der Namespace-Präfix des Attributs. |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Attributs. |
| ns | const [String](../../../system/string/)\& | Der Namespace-URI für das Attribut. |

## XmlWriter::WriteStartAttribute(const String\&) Methode

Schreibt den Beginn eines Attributs mit dem angegebenen lokalen Namen.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Der lokale Name des Attributs. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)