---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API संदर्भ
description: एट्रिब्यूट मान को एक या अधिक Text, EntityReference, या EndEntity नोड्स में पार्स करता है।
type: docs
weight: 560
url: /hi/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() मेथड


ऐट्रिब्यूट मान को एक या अधिक **[Text](../../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है।

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### रिटर्न मान

**true** यदि लौटाने के लिए नोड्स हैं। **false** यदि प्रारम्भिक कॉल के समय रीडर एट्रिब्यूट नोड पर स्थित नहीं है या यदि सभी एट्रिब्यूट मान पढ़ लिये गए हैं। एक खाली एट्रिब्यूट, जैसे **misc=\"\"**, **true** लौटाता है जिसमें एक एकल नोड का मान [String::Empty](../../../system/string/empty/) है।

## संबंधित देखें

* क्लास [XmlTextReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)