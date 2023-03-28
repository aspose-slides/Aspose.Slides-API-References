---
title: XmlTextReader()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the XmlTextReader class with the specified stream.
type: docs
weight: 482
url: /cpp/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML data to read. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL and stream.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML data to read. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified stream and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML data to read. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL, stream and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. If **url** is **nullptr**, **BaseURI** is set to [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML data to read. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The TextReader containing the XML data to read. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL and TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The TextReader containing the XML data to read. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified TextReader and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The TextReader containing the XML data to read. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified URL, TextReader and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL to use for resolving external resources. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. If **url** is **nullptr**, **BaseURI** is set to [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The TextReader containing the XML data to read. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\&, [XmlNodeType](../../xmlnodetype/), const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified stream, XmlNodeType, and [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML fragment to parse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the XML fragment. This also determines what the fragment can contain. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the **xmlFragment** is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang**, and the **xml:space** scope. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&, [XmlNodeType](../../xmlnodetype/), const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified string, XmlNodeType, and [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | The string containing the XML fragment to parse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the XML fragment. This also determines what the fragment string can contain. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the **xmlFragment** is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang**, and the **xml:space** scope. |

## See Also

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified file.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL for the file containing the XML data. The [XmlTextReader::get_BaseURI](../get_baseuri/) is set to this value. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlTextReader::XmlTextReader(const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&) constructor


Initializes a new instance of the [XmlTextReader](../) class with the specified file and [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | The URL for the file containing the XML data to read. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use. |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
