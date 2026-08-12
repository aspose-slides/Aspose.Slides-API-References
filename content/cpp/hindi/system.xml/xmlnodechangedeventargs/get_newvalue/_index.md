---
title: get_NewValue()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नोड का नया मान लौटाता है।
type: docs
weight: 66
url: /hi/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() मेथड

नोड का नया मान लौटाता है।

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### रिटर्न मान

नोड का नया मान। यह मेथड **nullptr** लौटाता है यदि नोड न तो एट्रिब्यूट है न ही टेक्स्ट नोड, या यदि नोड हटाया जा रहा है। यदि इसे **XmlDocument::NodeChanging** इवेंट में कॉल किया जाता है, तो **get_NewValue** नोड का मान लौटाता है यदि परिवर्तन सफल होता है। यदि इसे **XmlDocument::NodeChanged** इवेंट में कॉल किया जाता है, तो **get_NewValue** नोड का वर्तमान मान लौटाता है।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeChangedEventArgs](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)