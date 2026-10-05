---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new XmlReader instance with specified URI.
type: docs
weight: 1015
url: /system.xml/xmlreader/create/
---
## XmlReader::Create(const String&) method


Creates a new [XmlReader](../) instance with specified URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)& | The URI for the file that contains the XML data. The [XmlUrlResolver](../../xmlurlresolver/) class is used to convert the path to a canonical data representation. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **inputUri** value is **nullptr**. |
| SecurityException | The [XmlReader](../) does not have sufficient permissions to access the location of the XML data. |
| FileNotFoundException | The file identified by the URI does not exist. |
| UriFormatException | The URI format is not correct. |


## XmlReader::Create(const String&, const SharedPtr\<XmlReaderSettings\>&) method


Creates a new [XmlReader](../) instance by using the specified URI and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)& | The URI for the file containing the XML data. The [XmlResolver](../../xmlresolver/) object on the [XmlReaderSettings](../../xmlreadersettings/) object is used to convert the path to a canonical data representation. If XmlReaderSettings::get_XmlResolver value is **nullptr**, a new [XmlUrlResolver](../../xmlurlresolver/) object is used. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>& | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **inputUri** value is **nullptr**. |
| FileNotFoundException | The file specified by the URI cannot be found. |
| UriFormatException | The URI format is not correct. |


## XmlReader::Create(const String&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>&) method


Creates a new [XmlReader](../) instance by using the specified URI, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)& | The URI for the file containing the XML data. The [XmlResolver](../../xmlresolver/) object on the [XmlReaderSettings](../../xmlreadersettings/) object is used to convert the path to a canonical data representation. If XmlReaderSettings::get_XmlResolver value is **nullptr**, a new [XmlUrlResolver](../../xmlurlresolver/) object is used. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **inputUri** value is **nullptr**. |
| SecurityException | The [XmlReader](../) does not have sufficient permissions to access the location of the XML data. |
| ArgumentException | The [XmlReaderSettings::get_NameTable](../../xmlreadersettings/get_nametable/) and [XmlParserContext::get_NameTable](../../xmlparsercontext/get_nametable/) both are non-nullptr values. (Only one of these **[NameTable](../../nametable/)** values can be set and used). |
| FileNotFoundException | The file specified by the URI cannot be found. |
| UriFormatException | The URI format is not correct. |


## XmlReader::Create(const SharedPtr\<IO::Stream\>&) method


Creates a new [XmlReader](../) instance using the specified stream with default settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |
| SecurityException | The [XmlReader](../) does not have sufficient permissions to access the location of the XML data. |


## XmlReader::Create(const SharedPtr\<IO::Stream\>&, const SharedPtr\<XmlReaderSettings\>&) method


Creates a new [XmlReader](../) instance with the specified stream and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>& | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |


## XmlReader::Create(const SharedPtr\<IO::Stream\>&, SharedPtr\<XmlReaderSettings\>, const String&) method


Creates a new [XmlReader](../) instance using the specified stream, base URI, and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| baseUri | const [String](../../../system/string/)& | The base URI for the entity or document being read. This value can be **nullptr**. **[Security](../../../system.security/) Note** The base URI is used to resolve the relative URI of the XML document. Do not use a base URI from an untrusted source. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |


## XmlReader::Create(const SharedPtr\<IO::Stream\>&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>&) method


Creates a new [XmlReader](../) instance using the specified stream, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |


## XmlReader::Create(const SharedPtr\<IO::TextReader\>&) method


Creates a new [XmlReader](../) instance by using the specified text reader.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration is not used by the XML reader to decode the data stream. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |


## XmlReader::Create(const SharedPtr\<IO::TextReader\>&, const SharedPtr\<XmlReaderSettings\>&) method


Creates a new [XmlReader](../) instance by using the specified text reader and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the XML reader to decode the data stream. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>& | The settings for the new [XmlReader](../). This value can be **nullptr**. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |


## XmlReader::Create(const SharedPtr\<IO::TextReader\>&, SharedPtr\<XmlReaderSettings\>, const String&) method


Creates a new [XmlReader](../) instance by using the specified text reader, settings, and base URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the [XmlReader](../) to decode the data stream. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| baseUri | const [String](../../../system/string/)& | The base URI for the entity or document being read. This value can be **nullptr**. **[Security](../../../system.security/) Note** The base URI is used to resolve the relative URI of the XML document. Do not use a base URI from an untrusted source. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |


## XmlReader::Create(const SharedPtr\<IO::TextReader\>&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>&) method


Creates a new [XmlReader](../) instance by using the specified text reader, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the XML reader to decode the data stream. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### Return Value

An object that is used to read the XML data in the stream.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **input** value is **nullptr**. |
| ArgumentException | The [XmlReaderSettings::get_NameTable](../../xmlreadersettings/get_nametable/) and [XmlParserContext::get_NameTable](../../xmlparsercontext/get_nametable/) both are non-nullptr values. (Only one of these **[NameTable](../../nametable/)** values can be set and used). |


## XmlReader::Create(const SharedPtr\<XmlReader\>&, SharedPtr\<XmlReaderSettings\>) method


Creates a new [XmlReader](../) instance by using the specified XML reader and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>& | The object that you want to use as the underlying XML reader. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. The conformance level of the [XmlReaderSettings](../../xmlreadersettings/) object must either match the conformance level of the underlying reader, or it must be set to [ConformanceLevel::Auto](../../conformancelevel/). |

### Return Value

An object that is wrapped around the specified [XmlReader](../) object.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The **reader** value is **nullptr**. |
| InvalidOperationException | If the [XmlReaderSettings](../../xmlreadersettings/) object specifies a conformance level that is not consistent with conformance level of the underlying reader. The underlying [XmlReader](../) is in an [ReadState::Error](../../readstate/) or [ReadState::Closed](../../readstate/) state. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)