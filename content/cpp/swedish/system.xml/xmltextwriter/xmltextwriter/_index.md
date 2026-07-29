---
title: XmlTextWriter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av XmlTextWriter-klassen med den angivna strömmen och kodningen.
type: docs
weight: 183
url: /sv/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Skapar en instans av klassen [XmlTextWriter](../) med den angivna strömmen och kodningen.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen du vill skriva till. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodningen som ska genereras. Om kodning är **nullptr** skrivs strömmen ut som UTF-8 och kodningsattributet utelämnas från **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Skapar en instans av klassen [XmlTextWriter](../) med den angivna filen.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Filnamnet att skriva till. Om filen redan finns trunkeras den och skrivs över med det nya innehållet. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodningen som ska genereras. Om kodning är **nullptr** skrivs filen ut som UTF-8 och kodningsattributet utelämnas från **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) konstruktor


Skapar en instans av klassen [XmlTextWriter](../) med den angivna TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWritern att skriva till. Det antas att TextWritern redan är inställd på rätt kodning. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Class [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)