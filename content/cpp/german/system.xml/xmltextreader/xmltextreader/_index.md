---
title: XmlTextReader()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der XmlTextReader-Klasse mit dem angegebenen Stream.
type: docs
weight: 482
url: /de/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit dem angegebenen Stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die zu lesenden XML-Daten enthält. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen URL und dem Stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL, die zum Auflösen externer Ressourcen verwendet wird. Die [XmlTextReader::get_BaseURI](../get_baseuri/) wird auf diesen Wert gesetzt. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die zu lesenden XML-Daten enthält. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit dem angegebenen Stream und [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die zu lesenden XML-Daten enthält. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Die zu verwendende [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen URL, dem Stream und [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL, die zum Auflösen externer Ressourcen verwendet wird. Die [XmlTextReader::get_BaseURI](../get_baseuri/) wird auf diesen Wert gesetzt. Wenn **url** **nullptr** ist, wird **BaseURI** auf [String::Empty](../../../system/string/empty/) gesetzt. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der die zu lesenden XML-Daten enthält. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Die zu verwendende [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit dem angegebenen TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der TextReader, der die zu lesenden XML-Daten enthält. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen URL und dem TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL, die zum Auflösen externer Ressourcen verwendet wird. Die [XmlTextReader::get_BaseURI](../get_baseuri/) wird auf diesen Wert gesetzt. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der TextReader, der die zu lesenden XML-Daten enthält. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit dem angegebenen TextReader und [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der TextReader, der die zu lesenden XML-Daten enthält. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Die zu verwendende [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen URL, dem TextReader und [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL, die zum Auflösen externer Ressourcen verwendet wird. Die [XmlTextReader::get_BaseURI](../get_baseuri/) wird auf diesen Wert gesetzt. Wenn **url** **nullptr** ist, wird **BaseURI** auf [String::Empty](../../../system/string/empty/) gesetzt. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Der TextReader, der die zu lesenden XML-Daten enthält. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Die zu verwendende [XmlNameTable](../../xmlnametable/). |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit dem angegebenen Stream, XmlNodeType und [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Der Stream, der das zu parsende XML-Fragment enthält. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Der XmlNodeType des XML-Fragments. Dies bestimmt auch, was das Fragment enthalten kann. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Der [XmlParserContext](../../xmlparsercontext/) in dem **xmlFragment** zu parsen ist. Dies umfasst das zu verwendende [XmlNameTable](../../xmlnametable/), die Kodierung, den Namensraum-Geltungsbereich, das aktuelle **xml:lang** und den **xml:space**-Geltungsbereich. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen Zeichenkette, XmlNodeType und [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Die Zeichenkette, die das zu parsende XML-Fragment enthält. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Der XmlNodeType des XML-Fragments. Dies bestimmt auch, was die Fragment-Zeichenkette enthalten kann. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Der [XmlParserContext](../../xmlparsercontext/) in dem **xmlFragment** zu parsen ist. Dies umfasst das zu verwendende [XmlNameTable](../../xmlnametable/), die Kodierung, den Namensraum-Geltungsbereich, das aktuelle **xml:lang** und den **xml:space**-Geltungsbereich. |

## XmlTextReader::XmlTextReader(const String\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen Datei.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL der Datei, die die XML-Daten enthält. Die [XmlTextReader::get_BaseURI](../get_baseuri/) wird auf diesen Wert gesetzt. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) Konstruktor

Initialisiert eine neue Instanz der [XmlTextReader](../) Klasse mit der angegebenen Datei und [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Die URL der Datei, die die zu lesenden XML-Daten enthält. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Die zu verwendende [XmlNameTable](../../xmlnametable/). |

## Siehe Auch

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)