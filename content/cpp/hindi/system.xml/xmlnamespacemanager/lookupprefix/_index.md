---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API संदर्भ
description: दिए गए नेमस्पेस URI के लिए घोषित प्रीफ़िक्स को खोजता है।
type: docs
weight: 131
url: /hi/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) विधि

Given namespace URI के लिए घोषित प्रीफ़िक्स को खोजता है।

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | प्रीफ़िक्स के लिए हल करने हेतु नेमस्पेस। |

### वापसी मान

मिलता हुआ प्रीफ़िक्स। यदि कोई मैप्ड प्रीफ़िक्स नहीं है, तो विधि [String::Empty](../../../system/string/empty/) लौटाती है। यदि null मान प्रदान किया जाता है, तो **nullptr** वापस किया जाता है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNamespaceManager](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)