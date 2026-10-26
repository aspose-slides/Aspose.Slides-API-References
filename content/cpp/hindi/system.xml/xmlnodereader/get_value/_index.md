---
title: get_Value()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान नोड का टेक्स्ट मान लौटाता है।
type: docs
weight: 79
url: /hi/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() विधि

वर्तमान नोड का टेक्स्ट मान लौटाता है।

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### रिटर्न वैल्यू

प्राप्त मान नोड के [XmlNodeReader::get_NodeType](../get_nodetype/) पर निर्भर करता है।

## टिप्पणियाँ

निम्न तालिका उन नोड प्रकारों को सूचीबद्ध करती है जिनके पास लौटाने के लिए मान होता है। अन्य सभी नोड प्रकार [String::Empty](../../../system/string/empty/) लौटाते हैं।

| नोड प्रकार | मान |
| --- | --- |
| [Attribute](../../../system/attribute/)| एट्रिब्यूट का मान। |
| CDATA| CDATA सेक्शन की सामग्री। |
| Comment| टिप्पणी की सामग्री। |
| DocumentType| आंतरिक उपसमुच्चय। |
| ProcessingInstruction| लक्ष्य को छोड़कर पूरी सामग्री। |
| SignificantWhitespace| मिश्रित कंटेंट मॉडल में मार्कअप के बीच का भाग। |
| [Text](../../../system.text/)| टेक्स्ट नोड की सामग्री। |
| Whitespace| मार्कअप के बीच का भाग। |
| [XmlDeclaration](../../xmldeclaration/)| घोषणा की सामग्री। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)