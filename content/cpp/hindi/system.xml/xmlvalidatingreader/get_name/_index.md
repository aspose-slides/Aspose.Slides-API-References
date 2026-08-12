---
title: get_Name()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान नोड का योग्य नाम लौटाता है।
type: docs
weight: 14
url: /hi/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() मेथड


वर्तमान नोड का योग्य नाम लौटाता है।

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### रिटर्न वैल्यू

वर्तमान नोड का योग्य नाम। उदाहरण के लिए, **Name** तत्व **<bk:book>** के लिए **bk:book** है।

## टिप्पणी



वापस किया गया नाम नोड के XmlValidatingReader::NodeType पर निर्भर करता है। निम्नलिखित नोड प्रकार सूचीबद्ध मान लौटाते हैं। सभी अन्य नोड प्रकार एक खाली स्ट्रिंग लौटाते हैं। 

| नोड प्रकार | नाम |
| --- | --- |
| [Attribute](../../../system/attribute/)| विशेषता का नाम। |
| DocumentType| दस्तावेज़ प्रकार नाम। |
| Element| टैग का नाम। |
| EntityReference| संदर्भित इकाई का नाम। |
| ProcessingInstruction| प्रोसेसिंग इंस्ट्रक्शन का लक्ष्य। |
| [XmlDeclaration](../../xmldeclaration/)| लिटरल स्ट्रिंग `xml`। |


## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlValidatingReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)