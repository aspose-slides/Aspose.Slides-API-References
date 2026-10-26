---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट अनुक्रमणिका वाले विशेषता को लौटाता है।
type: docs
weight: 1
url: /hi/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) मेथड

निर्दिष्ट अनुक्रमणिका वाले विशेषता को लौटाता है।

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| i | **int32_t** | विशेषता की अनुक्रमणिका। |

### वापसी मान

निर्दिष्ट अनुक्रमणिका पर विशेषता।

## XmlAttributeCollection::idx_get(const String\&) मेथड

निर्दिष्ट नाम वाले विशेषता को लौटाता है।

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | विशेषता का योग्य नाम। |

### वापसी मान

निर्दिष्ट नाम वाली विशेषता। यदि विशेषता मौजूद नहीं है, तो यह मेथड **nullptr** लौटाता है।

## XmlAttributeCollection::idx_get(const String\&, const String\&) मेथड

निर्दिष्ट स्थानीय नाम और नामस्थान यूनिफॉर्म रिसोर्स आइडेंटिफायर (URI) वाले विशेषता को लौटाता है।

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | विशेषता का स्थानीय नाम। |
| namespaceURI | const [String](../../../system/string/)\& | विशेषता का नामस्थान URI। |

### वापसी मान

निर्दिष्ट स्थानीय नाम और नामस्थान URI वाली विशेषता। यदि विशेषता मौजूद नहीं है, तो यह मेथड **nullptr** लौटाता है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlAttribute](../../xmlattribute/)
* क्लास [XmlAttributeCollection](../)
* क्लास [String](../../../system/string/)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)