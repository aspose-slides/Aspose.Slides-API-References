---
title: Save()
second_title: Aspose.Slides för C++ API-referens
description: Sparar XML-dokumentet till den specificerade filen. Om den specificerade filen finns, skriver den här metoden över den.
type: docs
weight: 534
url: /sv/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metod

Sparar XML-dokumentet till den specificerade filen. Om den specificerade filen finns, skriver den här metoden över den.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Platsen för filen där du vill spara dokumentet. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metod

Sparar XML-dokumentet till den specificerade strömmen.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strömmen som du vill spara till. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metod

Sparar XML-dokumentet till den specificerade TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter som du vill spara till. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metod

Sparar XML-dokumentet till den specificerade [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | Den [XmlWriter](../../xmlwriter/) som du vill spara till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Klass [Stream](../../../system.io/stream/)
* Klass [TextWriter](../../../system.io/textwriter/)
* Klass [XmlWriter](../../xmlwriter/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)