---
title: XmlTextReader()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट स्ट्रीम के साथ XmlTextReader क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।
type: docs
weight: 482
url: /hi/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

निर्दिष्ट स्ट्रीम के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML डेटा को पढ़ने वाली स्ट्रीम। |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

निर्दिष्ट URL और स्ट्रीम के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला URL। [XmlTextReader::get_BaseURI](../get_baseuri/) को इस मान पर सेट किया जाता है। |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML डेटा को पढ़ने वाली स्ट्रीम। |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

निर्दिष्ट स्ट्रीम और [XmlNameTable](../../xmlnametable/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML डेटा को पढ़ने वाली स्ट्रीम। |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | उपयोग करने के लिए [XmlNameTable](../../xmlnametable/)। |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

निर्दिष्ट URL, स्ट्रीम और [XmlNameTable](../../xmlnametable/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला URL। [XmlTextReader::get_BaseURI](../get_baseuri/) को इस मान पर सेट किया जाता है। यदि **url** **nullptr** है, तो **BaseURI** [String::Empty](../../../system/string/empty/) पर सेट किया जाता है। |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML डेटा को पढ़ने वाली स्ट्रीम। |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | उपयोग करने के लिए [XmlNameTable](../../xmlnametable/)। |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

निर्दिष्ट TextReader के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML डेटा को पढ़ने वाला TextReader। |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

निर्दिष्ट URL और TextReader के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला URL। [XmlTextReader::get_BaseURI](../get_baseuri/) को इस मान पर सेट किया जाता है। |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML डेटा को पढ़ने वाला TextReader। |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

निर्दिष्ट TextReader और [XmlNameTable](../../xmlnametable/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML डेटा को पढ़ने वाला TextReader। |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | उपयोग करने के लिए [XmlNameTable](../../xmlnametable/)। |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

निर्दिष्ट URL, TextReader और [XmlNameTable](../../xmlnametable/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | बाहरी संसाधनों को हल करने के लिए उपयोग किया जाने वाला URL। [XmlTextReader::get_BaseURI](../get_baseuri/) को इस मान पर सेट किया जाता है। यदि **url** **nullptr** है, तो **BaseURI** [String::Empty](../../../system/string/empty/) पर सेट किया जाता है। |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML डेटा को पढ़ने वाला TextReader। |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | उपयोग करने के लिए [XmlNameTable](../../xmlnametable/)। |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

निर्दिष्ट स्ट्रीम, XmlNodeType और [XmlParserContext](../../xmlparsercontext/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML फ्रैगमेंट को पार्स करने वाली स्ट्रीम। |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML फ्रैगमेंट का XmlNodeType। यह यह भी निर्धारित करता है कि फ्रैगमेंट क्या रख सकता है। |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) जिसमें **xmlFragment** को पार्स किया जाना है। इसमें उपयोग करने के लिए [XmlNameTable](../../xmlnametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang**, और **xml:space** स्कोप शामिल हैं। |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

निर्दिष्ट स्ट्रिंग, XmlNodeType और [XmlParserContext](../../xmlparsercontext/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | XML फ्रैगमेंट को पार्स करने वाली स्ट्रिंग। |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML फ्रैगमेंट का XmlNodeType। यह यह भी निर्धारित करता है कि फ्रैगमेंट स्ट्रिंग क्या रख सकती है। |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) जिसमें **xmlFragment** को पार्स किया जाना है। इसमें उपयोग करने के लिए [XmlNameTable](../../xmlnametable/), एन्कोडिंग, नेमस्पेस स्कोप, वर्तमान **xml:lang**, और **xml:space** स्कोप शामिल हैं। |

## XmlTextReader::XmlTextReader(const String\&) constructor

निर्दिष्ट फ़ाइल के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | XML डेटा वाला फ़ाइल URL। [XmlTextReader::get_BaseURI](../get_baseuri/) को इस मान पर सेट किया जाता है। |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

निर्दिष्ट फ़ाइल और [XmlNameTable](../../xmlnametable/) के साथ [XmlTextReader](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | XML डेटा वाला फ़ाइल URL। |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | उपयोग करने के लिए [XmlNameTable](../../xmlnametable/)। |

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