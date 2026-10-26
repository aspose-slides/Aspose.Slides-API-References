---
title: get_LocalName()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड का स्थानीय नाम लौटाता है।
type: docs
weight: 27
url: /hi/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() विधि


वर्तमान नोड का स्थानीय नाम लौटाता है।

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### रिटर्न वैल्यू

वर्तमान नोड का नाम, जिसमें प्रीफ़िक्स हटा दिया गया है। उदाहरण के लिए, **LocalName** तत्व **<bk:book>** के लिए **book** है। उन नोड प्रकारों के लिए जिनका कोई नाम नहीं होता (जैसे **[Text](../../../system.text/)**, **Comment**, आदि), यह विधि [String::Empty](../../../system/string/empty/) लौटाती है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlValidatingReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)