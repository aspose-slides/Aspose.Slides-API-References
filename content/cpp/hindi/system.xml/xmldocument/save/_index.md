---
title: Save()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ाइल में XML दस्तावेज़ को सहेजता है। यदि निर्दिष्ट फ़ाइल पहले से मौजूद है, तो यह मेथड उसे अधिलेखित कर देता है।
type: docs
weight: 534
url: /hi/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) method

XML दस्तावेज़ को निर्दिष्ट फ़ाइल में सहेजता है। यदि निर्दिष्ट फ़ाइल मौजूद है, तो यह विधि इसे अधिलेखित कर देती है।

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | [String](../../../system/string/) | फ़ाइल का स्थान जहाँ आप दस्तावेज़ सहेजना चाहते हैं। |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) method

XML दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | वह स्ट्रीम जहाँ आप सहेजना चाहते हैं। |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) method

XML दस्तावेज़ को निर्दिष्ट TextWriter में सहेजता है।

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | वह TextWriter जहाँ आप सहेजना चाहते हैं। |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) method

XML दस्तावेज़ को निर्दिष्ट [XmlWriter](../../xmlwriter/) में सहेजता है।

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | वह [XmlWriter](../../xmlwriter/) जहाँ आप सहेजना चाहते हैं। |

## संबंधित

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [XmlDocument](../)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [TextWriter](../../../system.io/textwriter/)
* क्लास [XmlWriter](../../xmlwriter/)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)