---
title: XmlTextWriter()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een instantie van de XmlTextWriter-klasse aan met de opgegeven stream en codering.
type: docs
weight: 183
url: /nl/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

Maakt een instantie van de [XmlTextWriter](../) klasse aan met de opgegeven stream en codering.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | De stream waarnaar u wilt schrijven. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | De te genereren codering. Als codering **nullptr** is, schrijft het de stream uit als UTF-8 en laat het attribuut encoding weg in de **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor

Maakt een instantie van de [XmlTextWriter](../) klasse aan met het opgegeven bestand.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De bestandsnaam om naar te schrijven. Als het bestand bestaat, wordt het getruncateerd en wordt de inhoud overschreven met de nieuwe inhoud. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | De te genereren codering. Als codering **nullptr** is, schrijft het het bestand uit als UTF-8 en laat het attribuut encoding weg in de **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor

Maakt een instantie van de [XmlTextWriter](../) klasse aan met de opgegeven TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | De TextWriter om naar te schrijven. Er wordt aangenomen dat de TextWriter al is ingesteld op de juiste codering. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Class [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)