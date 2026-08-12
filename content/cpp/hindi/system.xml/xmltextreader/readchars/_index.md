---
title: ReadChars()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक तत्व की पाठ सामग्री को एक अक्षर बफ़र में पढ़ता है। यह विधि एम्बेडेड पाठ की बड़ी धारा को क्रमिक रूप से कॉल करके पढ़ने के लिए डिज़ाइन की गई है।
type: docs
weight: 755
url: /hi/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) विधि

एक तत्व की पाठ सामग्री को एक अक्षर बफ़र में पढ़ता है। यह विधि एम्बेडेड पाठ की बड़ी धारा को क्रमिक रूप से कॉल करके पढ़ने के लिए डिज़ाइन की गई है।

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | अक्षरों की वह सरणी जो buffer के रूप में कार्य करती है, जिसमें पाठ सामग्री लिखी जाती है। |
| index | **int32_t** | उस स्थान को **buffer** के भीतर जहाँ विधि पाठ सामग्री लिखना शुरू कर सकती है। |
| count | **int32_t** | **buffer** में लिखने के लिए अक्षरों की संख्या। |

### रिटर्न मान

पढ़े गए अक्षरों की संख्या। यदि रीडर किसी तत्व पर नहीं स्थित है या वर्तमान संदर्भ में लौटाने के लिए और कोई पाठ सामग्री नहीं है तो यह 0 हो सकता है।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)