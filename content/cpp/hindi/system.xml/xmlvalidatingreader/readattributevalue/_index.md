---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API संदर्भ
description: विशेषता मान को एक या अधिक Text, EntityReference, या EndEntity नोड्स में पार्स करता है।
type: docs
weight: 508
url: /hi/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() विधि

विशेषता मान को एक या अधिक **[Text](../../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है।

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### रिटर्न मान

**true** यदि लौटाने के लिए नोड्स हैं। **false** यदि रीडर प्रारम्भिक कॉल के समय attribute node पर स्थित नहीं है या सभी attribute मान पढ़ लिए गये हों। खाली attribute, जैसे, **misc=\"\"**, **true** लौटाता है जिसमें एकल नोड का मान [String::Empty](../../../system/string/empty/) होता है।

## देखें

* क्लास [XmlValidatingReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)