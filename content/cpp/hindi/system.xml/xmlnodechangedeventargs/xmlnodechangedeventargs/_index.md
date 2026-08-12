---
title: XmlNodeChangedEventArgs()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: XmlNodeChangedEventArgs क्लास का नया उदाहरण प्रारंभ करता है।
type: docs
weight: 79
url: /hi/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) कंस्ट्रक्टर

एक नया [XmlNodeChangedEventArgs](../) क्लास का उदाहरण प्रारंभ करता है।

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) जो इवेंट उत्पन्न करता है। |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | इवेंट उत्पन्न करने वाले [XmlNode](../../xmlnode/) का पुराना पैरेंट [XmlNode](../../xmlnode/)। |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | इवेंट उत्पन्न करने वाले [XmlNode](../../xmlnode/) का नया पैरेंट [XmlNode](../../xmlnode/)। |
| oldValue | const [String](../../../system/string/)\& | इवेंट उत्पन्न करने वाले [XmlNode](../../xmlnode/) का पुराना मान। |
| newValue | const [String](../../../system/string/)\& | इवेंट उत्पन्न करने वाले [XmlNode](../../xmlnode/) का नया मान। |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction। |

## संबंधित देखें

* एन्यूम [XmlNodeChangedAction](../../xmlnodechangedaction/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNode](../../xmlnode/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNodeChangedEventArgs](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)