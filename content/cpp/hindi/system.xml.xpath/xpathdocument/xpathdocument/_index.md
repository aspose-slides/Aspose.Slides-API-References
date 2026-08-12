---
title: XPathDocument()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XmlReader ऑब्जेक्ट में निहित XML डेटा से XPathDocument क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।
type: docs
weight: 1
url: /hi/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) निर्माता

निर्दिष्ट [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट में निहित XML डेटा से [XPathDocument](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | वह [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट जो XML डेटा को समाहित करता है। |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) निर्माता

निर्दिष्ट [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट में निहित XML डेटा और निर्दिष्ट व्हाइट स्पेस हैंडलिंग से [XPathDocument](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | वह [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट जो XML डेटा को समाहित करता है। |
| space | [XmlSpace](../../../system.xml/xmlspace/) | एक XmlSpace ऑब्जेक्ट। |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) निर्माता

निर्दिष्ट TextReader ऑब्जेक्ट में निहित XML डेटा से [XPathDocument](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML डेटा को समाहित करने वाला TextReader ऑब्जेक्ट। |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) निर्माता

निर्दिष्ट Stream ऑब्जेक्ट में निहित XML डेटा से [XPathDocument](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML डेटा को समाहित करने वाला Stream ऑब्जेक्ट। |

## XPathDocument::XPathDocument(const String\&) निर्माता

निर्दिष्ट फ़ाइल में मौजूद XML डेटा से [XPathDocument](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | फ़ाइल का पाथ जो XML डेटा को समाहित करती है। |

## XPathDocument::XPathDocument(const String\&, XmlSpace) निर्माता

निर्दिष्ट व्हाइट स्पेस हैंडलिंग के साथ फ़ाइल में मौजूद XML डेटा से [XPathDocument](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | फ़ाइल का पाथ जो XML डेटा को समाहित करती है। |
| space | [XmlSpace](../../../system.xml/xmlspace/) | एक XmlSpace ऑब्जेक्ट। |

## देखें भी

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathDocument](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)