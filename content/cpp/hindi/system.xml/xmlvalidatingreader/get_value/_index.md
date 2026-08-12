---
title: get_Value()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान नोड का पाठ मान लौटाता है।
type: docs
weight: 79
url: /hi/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() मेथड

वर्तमान नोड का पाठ मान लौटाता है।

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### रिटर्न मान

वापस किया गया मान नोड के XmlValidatingReader::NodeType पर निर्भर करता है।

## टिप्पणियाँ

निम्न तालिका उन नोड प्रकारों को सूचीबद्ध करती है जिनके पास लौटाने के लिए मान होता है। सभी अन्य नोड प्रकार [String::Empty](../../../system/string/empty/) लौटाते हैं।

| नोड प्रकार | मान |
| --- | --- |
| [Attribute](../../../system/attribute/)| विशेषता का मान। |
| CDATA| CDATA अनुभाग की सामग्री। |
| Comment| टिप्पणी की सामग्री। |
| DocumentType| आंतरिक उपसमुच्चय। |
| ProcessingInstruction| लक्ष्य को छोड़कर पूरी सामग्री। |
| SignificantWhitespace| मिश्रित सामग्री मॉडल में मार्कअप के बीच की सफेद जगह। |
| [Text](../../../system.text/)| पाठ नोड की सामग्री। |
| Whitespace| मार्कअप के बीच की सफेद जगह। |
| [XmlDeclaration](../../xmldeclaration/)| घोषणा की सामग्री। |

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlValidatingReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)