---
title: ReadAttributeValue()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एट्रीब्यूट वैल्यू को एक या अधिक Text, EntityReference, या EndEntity नोड्स में पार्स करता है।
type: docs
weight: 430
url: /hi/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() मेथड

एट्रीब्यूट वैल्यू को एक या अधिक **[Text](../../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है।

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### रिटर्न वैल्यू

**true** यदि रिटर्न करने के लिये नोड्स हैं। **false** यदि प्रारम्भिक कॉल के समय रीडर एट्रीब्यूट नोड पर स्थित नहीं है या सभी एट्रीब्यूट वैल्यू पढ़ ली गई हों। एक खाली एट्रीब्यूट, जैसे **misc=\"\"**, **true** लौटाता है जिसमें एकल नोड का मान [String::Empty](../../../system/string/empty/) होता है।

## संबंधित देखें

* क्लास [XmlNodeReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)