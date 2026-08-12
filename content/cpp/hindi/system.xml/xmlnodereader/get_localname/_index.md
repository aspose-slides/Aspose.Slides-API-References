---
title: get_LocalName()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: वर्तमान नोड का स्थानीय नाम लौटाता है।
type: docs
weight: 27
url: /hi/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() विधि

वर्तमान नोड का स्थानीय नाम वापस करता है।

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### वापसी मान

वर्तमान नोड का नाम, जिसमें उपसर्ग हटाया गया है। उदाहरण के लिए, **LocalName** तत्व **<bk:book>** के लिए **book** है। उन नोड प्रकारों के लिए जिनका कोई नाम नहीं होता (जैसे **[Text](../../../system.text/)**, **Comment**, आदि), यह विधि [String::Empty](../../../system/string/empty/) लौटाती है।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)