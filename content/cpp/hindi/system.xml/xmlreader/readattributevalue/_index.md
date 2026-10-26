---
title: ReadAttributeValue()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो एट्रिब्यूट वैल्यू को एक या अधिक Text, EntityReference, या EndEntity नोड्स में पार्स करता है।
type: docs
weight: 677
url: /hi/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() मेथड

When overridden in a derived class, parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### रिटर्न वैल्यू

**true** यदि लौटाने के लिए नोड्स हैं। **false** यदि प्रारंभिक कॉल के समय रीडर attribute नोड पर स्थित नहीं है या यदि सभी attribute मान पढ़ लिए गए हैं। एक खाली attribute, जैसे, **misc=\"\"**, **true** लौटाता है जिसमें एक एकल नोड होता है जिसका मान [String::Empty](../../../system/string/empty/)।

## संबंधित देखें

* क्लास [XmlReader](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)