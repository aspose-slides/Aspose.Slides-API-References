---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया XmlDocumentType ऑब्जेक्ट लौटाता है।
type: docs
weight: 313
url: /hi/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) विधि

एक नया [XmlDocumentType](../../xmldocumenttype/) ऑब्जेक्ट लौटाता है।

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | दस्तावेज़ प्रकार का नाम। |
| publicId | const [String](../../../system/string/)\& | दस्तावेज़ प्रकार का सार्वजनिक पहचानकर्ता या **nullptr**। आप एक सार्वजनिक URI और साथ ही एक सिस्टम पहचानकर्ता निर्दिष्ट करके बाहरी DTD उपसमुच्चय का स्थान पहचान सकते हैं। |
| systemId | const [String](../../../system/string/)\& | दस्तावेज़ प्रकार का सिस्टम पहचानकर्ता या **nullptr**। बाहरी DTD उपसमुच्चय के फ़ाइल स्थान का URL निर्दिष्ट करता है। |
| internalSubset | const [String](../../../system/string/)\& | दस्तावेज़ प्रकार का DTD आंतरिक उपसमुच्चय या **nullptr**। |

### रिटर्न वैल्यू

नया [XmlDocumentType](../../xmldocumenttype/)।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlDocumentType](../../xmldocumenttype/)
* क्लास [String](../../../system/string/)
* क्लास [XmlDocument](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)