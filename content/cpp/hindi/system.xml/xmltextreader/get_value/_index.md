---
title: get_Value()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: वर्तमान नोड का टेक्स्ट मान लौटाता है।
type: docs
weight: 79
url: /hi/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() विधि


वर्तमान नोड का टेक्स्ट मान लौटाता है।

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### रिटर्न मान

रिटर्न किया गया मान नोड के [XmlTextReader::get_NodeType](../get_nodetype/) मान पर निर्भर करता है।

## टिप्पणियाँ



निम्न तालिका उन नोड प्रकारों को सूचीबद्ध करती है जिनके पास रिटर्न करने योग्य मान होता है। सभी अन्य नोड प्रकार [String::Empty](../../../system/string/empty/) लौटाते हैं। 

| नोड प्रकार | मान |
| --- | --- |
| [Attribute](../../../system/attribute/)| एट्रिब्यूट का मान। |
| CDATA| CDATA सेक्शन की सामग्री। |
| Comment| टिप्पणी की सामग्री। |
| DocumentType| आंतरिक उपसमुच्चय। |
| ProcessingInstruction| पूरा कंटेंट, लक्ष्य को छोड़कर। |
| SignificantWhitespace| `xml:space='preserve'` स्कोप के भीतर का व्हाइटस्पेस। |
| [Text](../../../system.text/)| टेक्स्ट नोड की सामग्री। |
| Whitespace| मार्कअप के बीच का व्हाइटस्पेस। |
| [XmlDeclaration](../../xmldeclaration/)| घोषणा की सामग्री। |


## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlTextReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)