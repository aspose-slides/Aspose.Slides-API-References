---
title: InsertBefore()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट एट्रिब्यूट को तुरंत निर्दिष्ट संदर्भ एट्रिब्यूट के पहले डालता है।
type: docs
weight: 53
url: /hi/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) मेथड

निर्दिष्ट एट्रिब्यूट को तुरंत निर्दिष्ट रेफ़रेंस एट्रिब्यूट के पहले डालता है।

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | डालने के लिए एट्रिब्यूट। |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | रेफ़रेंस एट्रिब्यूट। **newNode** is placed before the **refNode**। |

### वापसी मान

[XmlAttribute](../../xmlattribute/) को संग्रह में डालने के लिए।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlAttribute](../../xmlattribute/)
* क्लास [XmlAttributeCollection](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)