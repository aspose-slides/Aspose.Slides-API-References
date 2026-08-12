---
title: XmlTextWriter()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: निर्दिष्ट स्ट्रीम और एन्कोडिंग का उपयोग करके XmlTextWriter क्लास का एक उदाहरण बनाता है।
type: docs
weight: 183
url: /hi/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) कंस्ट्रक्टर

निर्दिष्ट स्ट्रीम और एन्कोडिंग का उपयोग करके [XmlTextWriter](../) क्लास का एक उदाहरण बनाता है।

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | जिस स्ट्रीम में आप लिखना चाहते हैं। |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | जनरेट करने के लिए एन्कोडिंग। यदि एन्कोडिंग **nullptr** है तो यह स्ट्रीम को UTF-8 के रूप में लिखता है और **ProcessingInstruction** से एन्कोडिंग एट्रीब्यूट को हटाता है। |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) कंस्ट्रक्टर

निर्दिष्ट फ़ाइल का उपयोग करके [XmlTextWriter](../) क्लास का एक उदाहरण बनाता है।

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | लिखने के लिए फ़ाइलनाम। यदि फ़ाइल मौजूद है, तो यह उसे ट्रंकेट कर नई सामग्री के साथ ओवरराइट कर देता है। |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | जनरेट करने के लिए एन्कोडिंग। यदि एन्कोडिंग **nullptr** है तो यह फ़ाइल को UTF-8 के रूप में लिखता है और **ProcessingInstruction** से एन्कोडिंग एट्रीब्यूट को हटाता है। |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) कंस्ट्रक्टर

निर्दिष्ट TextWriter का उपयोग करके [XmlTextWriter](../) क्लास का एक उदाहरण बनाता है।

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | लिखने के लिए TextWriter। माना जाता है कि TextWriter पहले से ही सही एन्कोडिंग पर सेट है। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Class [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)