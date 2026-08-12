---
title: WriteStartElement()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्दिष्ट प्रारम्भ टैग को लिखता है और उसे दिए गए नेमस्पेस और प्रीफ़िक्स के साथ जोड़ता है।
type: docs
weight: 235
url: /hi/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) मेथड

निर्दिष्ट प्रारम्भ टैग को लिखता है और उसे दिए गए नेमस्पेस और प्रीफ़िक्स के साथ जोड़ता है।

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | तत्व का नेमस्पेस प्रीफ़िक्स। |
| localName | const [String](../../../system/string/)\& | तत्व का स्थानीय नाम। |
| ns | const [String](../../../system/string/)\& | तत्व के साथ जोड़े जाने वाला नेमस्पेस URI। यदि यह नेमस्पेस पहले से ही स्कोप में है और उसका संबंधित प्रीफ़िक्स है तो राइटर स्वचालित रूप से वह प्रीफ़िक्स भी लिख देगा। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlTextWriter](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)