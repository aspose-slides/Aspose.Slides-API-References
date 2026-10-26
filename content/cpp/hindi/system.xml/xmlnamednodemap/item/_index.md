---
title: Item()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट अनुक्रमणिका पर XmlNamedNodeMap में नोड को प्राप्त करता है।
type: docs
weight: 53
url: /hi/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) मेथड

निर्दिष्ट अनुक्रमणिका पर [XmlNamedNodeMap](../) में नोड को प्राप्त करता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | [XmlNamedNodeMap](../) से नोड को प्राप्त करने के लिये अनुक्रमणिका स्थिति। अनुक्रमणिका शून्य-आधारित है; इसलिए, पहले नोड की अनुक्रमणिका 0 है और अंतिम नोड की अनुक्रमणिका [XmlNamedNodeMap::get_Count](../get_count/) - 1 है। |

### वापसी मान

निर्दिष्ट अनुक्रमणिका पर [XmlNode](../../xmlnode/)। यदि **index** 0 से कम है या [XmlNamedNodeMap::get_Count](../get_count/) मान के बराबर या उससे बड़ा है, तो **nullptr** लौटाया जाता है।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlNamedNodeMap](../)
* नेमस्पेस [System::Xml](../../)
* Library [Aspose.Slides](../../../)