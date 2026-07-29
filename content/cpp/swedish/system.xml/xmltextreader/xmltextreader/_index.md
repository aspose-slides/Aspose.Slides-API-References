---
title: XmlTextReader()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av XmlTextReader-klassen med den angivna strömmen.
type: docs
weight: 482
url: /sv/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna strömmen.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data att läsa. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna URL:en och strömmen.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL:en att använda för att lösa externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data att läsa. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna strömmen och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data att läsa. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna URL:en, strömmen och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL:en att använda för att lösa externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. Om **url** är **nullptr**, sätts **BaseURI** till [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-data att läsa. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader:n som innehåller XML-data att läsa. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna URL:en och TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL:en att använda för att lösa externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader:n som innehåller XML-data att läsa. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna TextReader och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader:n som innehåller XML-data att läsa. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna URL:en, TextReader och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL:en att använda för att lösa externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. Om **url** är **nullptr**, sätts **BaseURI** till [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader:n som innehåller XML-data att läsa. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna strömmen, XmlNodeType och [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strömmen som innehåller XML-fragmentet att tolka. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType för XML-fragmentet. Detta bestämmer också vad fragmentet kan innehålla. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) där **xmlFragment** ska tolkas. Detta inkluderar [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsomfång, den aktuella **xml:lang**, och **xml:space**-omfånget. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna strängen, XmlNodeType och [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Strängen som innehåller XML-fragmentet att tolka. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType för XML-fragmentet. Detta bestämmer också vad fragmentsträngen kan innehålla. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) där **xmlFragment** ska tolkas. Detta inkluderar [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsomfång, den aktuella **xml:lang**, och **xml:space**-omfånget. |

## XmlTextReader::XmlTextReader(const String\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna filen.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL:en för filen som innehåller XML-data. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

Initierar en ny instans av klass [XmlTextReader](../) med den angivna filen och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL:en för filen som innehåller XML-data att läsa. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## See Also

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