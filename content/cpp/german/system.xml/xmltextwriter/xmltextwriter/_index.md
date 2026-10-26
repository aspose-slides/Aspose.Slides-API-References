---
title: XmlTextWriter()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine Instanz der XmlTextWriter-Klasse mit dem angegebenen Stream und der angegebenen Codierung.
type: docs
weight: 183
url: /de/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) Konstruktor

Erstellt eine Instanz der [XmlTextWriter](../)-Klasse mit dem angegebenen Stream und der angegebenen Codierung.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, in den Sie schreiben möchten. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Die zu erzeugende Codierung. Wenn die Codierung **nullptr** ist, wird der Stream als UTF-8 ausgegeben und das Codierungs-Attribut aus der **ProcessingInstruction** weggelassen. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) Konstruktor

Erstellt eine Instanz der [XmlTextWriter](../)-Klasse mit der angegebenen Datei.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Der Dateiname, in den geschrieben werden soll. Wenn die Datei existiert, wird sie abgeschnitten und mit dem neuen Inhalt überschrieben. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Die zu erzeugende Codierung. Wenn die Codierung **nullptr** ist, wird die Datei als UTF-8 ausgegeben und das Codierungs-Attribut aus der **ProcessingInstruction** weggelassen. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) Konstruktor

Erstellt eine Instanz der [XmlTextWriter](../)-Klasse mit dem angegebenen TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Der TextWriter, in den geschrieben werden soll. Es wird davon ausgegangen, dass der TextWriter bereits auf die richtige Codierung eingestellt ist. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [Encoding](../../../system.text/encoding/)
* Klasse [XmlTextWriter](../)
* Klasse [String](../../../system/string/)
* Klasse [TextWriter](../../../system.io/textwriter/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)