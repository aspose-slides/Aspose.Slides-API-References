---
title: Create()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نسخة جديدة من XmlReader باستخدام URI المحدد.
type: docs
weight: 1015
url: /ar/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) طريقة

Creates a new [XmlReader](../) instance with specified URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI for the file that contains the XML data. The [XmlUrlResolver](../../xmlurlresolver/) class is used to convert the path to a canonical data representation. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) طريقة

Creates a new [XmlReader](../) instance by using the specified URI and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI for the file containing the XML data. The [XmlResolver](../../xmlresolver/) object on the [XmlReaderSettings](../../xmlreadersettings/) object is used to convert the path to a canonical data representation. If XmlReaderSettings::get_XmlResolver value is **nullptr**, a new [XmlUrlResolver](../../xmlurlresolver/) object is used. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) طريقة

Creates a new [XmlReader](../) instance by using the specified URI, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | The URI for the file containing the XML data. The [XmlResolver](../../xmlresolver/) object on the [XmlReaderSettings](../../xmlreadersettings/) object is used to convert the path to a canonical data representation. If XmlReaderSettings::get_XmlResolver value is **nullptr**, a new [XmlUrlResolver](../../xmlurlresolver/) object is used. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) طريقة

Creates a new [XmlReader](../) instance using the specified stream with default settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) طريقة

Creates a new [XmlReader](../) instance with the specified stream and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) طريقة

Creates a new [XmlReader](../) instance using the specified stream, base URI, and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | The base URI for the entity or document being read. This value can be **nullptr**. **[Security](../../../system.security/) ملاحظة** The base URI is used to resolve the relative URI of the XML document. Do not use a base URI from an untrusted source. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) طريقة

Creates a new [XmlReader](../) instance using the specified stream, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream that contains the XML data. The [XmlReader](../) scans the first bytes of the stream looking for a byte order mark or other sign of encoding. When encoding is determined, the encoding is used to continue reading the stream, and processing continues parsing the input as a stream of (Unicode) characters. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) طريقة

Creates a new [XmlReader](../) instance by using the specified text reader.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration is not used by the XML reader to decode the data stream. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) طريقة

Creates a new [XmlReader](../) instance by using the specified text reader and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the XML reader to decode the data stream. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | The settings for the new [XmlReader](../). This value can be **nullptr**. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) طريقة

Creates a new [XmlReader](../) instance by using the specified text reader, settings, and base URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the [XmlReader](../) to decode the data stream. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | The base URI for the entity or document being read. This value can be **nullptr**. **[Security](../../../system.security/) ملاحظة** The base URI is used to resolve the relative URI of the XML document. Do not use a base URI from an untrusted source. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) طريقة

Creates a new [XmlReader](../) instance by using the specified text reader, settings, and context information for parsing.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | The text reader from which to read the XML data. A text reader returns a stream of Unicode characters, so the encoding specified in the XML declaration isn't used by the XML reader to decode the data stream. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. This value can be **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The context information required to parse the XML fragment. The context information can include the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, the current **xml:lang** and **xml:space** scope, base URI, and document type definition. This value can be **nullptr**. |

### قيمة الإرجاع

An object that is used to read the XML data in the stream.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) طريقة

Creates a new [XmlReader](../) instance by using the specified XML reader and settings.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | The object that you want to use as the underlying XML reader. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | The settings for the new [XmlReader](../) instance. The conformance level of the [XmlReaderSettings](../../xmlreadersettings/) object must either match the conformance level of the underlying reader, or it must be set to [ConformanceLevel::Auto](../../conformancelevel/). |

### قيمة الإرجاع

An object that is wrapped around the specified [XmlReader](../) object.

## انظر أيضًا

* نوع تعريف [SharedPtr](../../../system/sharedptr/)
* فئة [XmlReader](../)
* فئة [String](../../../system/string/)
* فئة [XmlReaderSettings](../../xmlreadersettings/)
* فئة [XmlParserContext](../../xmlparsercontext/)
* فئة [Stream](../../../system.io/stream/)
* فئة [TextReader](../../../system.io/textreader/)
* نطاق الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)