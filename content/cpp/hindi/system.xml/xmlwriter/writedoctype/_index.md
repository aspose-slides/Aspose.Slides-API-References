---
title: WriteDocType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह निर्दिष्ट नाम और वैकल्पिक गुणों के साथ DOCTYPE घोषणा लिखता है।
type: docs
weight: 79
url: /hi/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) विधि

जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तब यह निर्दिष्ट नाम और वैकल्पिक गुणों के साथ DOCTYPE घोषणा लिखता है।

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE का नाम। यह खाली नहीं होना चाहिए। |
| pubid | const [String](../../../system/string/)\& | यदि non-null है तो यह PUBLIC "pubid" "sysid" भी लिखता है जहाँ **pubid** और **sysid** को दी गई तर्कों के मान से बदला जाता है। |
| sysid | const [String](../../../system/string/)\& | यदि **pubid** **nullptr** है और **sysid** non-null है तो यह SYSTEM "sysid" लिखता है जहाँ **sysid** को इस तर्क के मान से बदला जाता है। |
| subset | const [String](../../../system/string/)\& | यदि non-null है तो यह [subset] लिखता है जहाँ subset को इस तर्क के मान से बदला जाता है। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlWriter](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)