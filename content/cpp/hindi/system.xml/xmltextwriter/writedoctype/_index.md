---
title: WriteDocType()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट नाम और वैकल्पिक गुणों के साथ DOCTYPE घोषणा लिखता है।
type: docs
weight: 222
url: /hi/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) मेथड

निर्दिष्ट नाम और वैकल्पिक गुणों के साथ DOCTYPE घोषणा लिखता है।

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE का नाम। यह खाली नहीं होना चाहिए। |
| pubid | const [String](../../../system/string/)\& | यदि नॉन-नल है तो यह PUBLIC \"pubid\" \"sysid\" भी लिखता है जहाँ **pubid** और **sysid** को दिए गए तर्कों के मान से बदला जाता है। |
| sysid | const [String](../../../system/string/)\& | यदि **pubid** नल है और **sysid** नॉन-नल है तो यह SYSTEM \"sysid\" लिखता है जहाँ **sysid** को इस तर्क के मान से बदला जाता है। |
| subset | const [String](../../../system/string/)\& | यदि नॉन-नल है तो यह [subset] लिखता है जहाँ subset को इस तर्क के मान से बदला जाता है। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlTextWriter](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)