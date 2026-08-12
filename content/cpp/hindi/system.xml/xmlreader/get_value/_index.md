---
title: get_Value()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो वर्तमान नोड का पाठ मान प्राप्त करता है।
type: docs
weight: 92
url: /hi/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() मेथड

जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो वर्तमान नोड का पाठ मान प्राप्त करता है।

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### रिटर्न मान

वापस किया गया मान नोड के [XmlReader::get_NodeType](../get_nodetype/) मान पर निर्भर करता है।

## टिप्पणियाँ

निम्न तालिका उन नोड प्रकारों को दर्शाती है जिनके पास लौटाने के लिए मान होता है। सभी अन्य नोड प्रकार [String::Empty](../../../system/string/empty/) लौटाते हैं। 

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| एट्रिब्यूट का मान। |
| `CDATA`| CDATA सेक्शन की सामग्री। |
| `Comment`| टिप्पणी की सामग्री। |
| `DocumentType`| आंतरिक उपसमुच्चय। |
| `ProcessingInstruction`| संपूर्ण सामग्री, लक्ष्य को छोड़ कर। |
| `SignificantWhitespace`| मिश्रित सामग्री मॉडल में मार्कअप के बीच का सफ़ेद स्थान। |
| `[Text](../../../system.text/)`| टेक्स्ट नोड की सामग्री। |
| `Whitespace`| मार्कअप के बीच का सफ़ेद स्थान। |
| [XmlDeclaration](../../xmldeclaration/)| घोषणा की सामग्री। |

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)