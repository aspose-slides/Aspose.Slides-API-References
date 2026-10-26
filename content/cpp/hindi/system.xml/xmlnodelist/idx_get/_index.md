---
title: idx_get()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: दिये गये इंडेक्स पर एक नोड लौटाता है।
type: docs
weight: 40
url: /hi/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) मेथड


दिए गए इंडेक्स पर node लौटाता है।

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| i | **int32_t** | सूची में nodes का शून्य-आधारित इंडेक्स। |

### रिटर्न वैल्यू

संग्रह में निर्दिष्ट इंडेक्स वाला [XmlNode](../../xmlnode/)। यदि इंडेक्स सूची में nodes की संख्या से बड़ा या बराबर है, तो यह **nullptr** लौटाता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [XmlNodeList](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)