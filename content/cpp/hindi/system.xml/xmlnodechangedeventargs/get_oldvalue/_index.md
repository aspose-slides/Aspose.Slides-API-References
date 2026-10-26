---
title: get_OldValue()
second_title: Aspose.Slides for C++ API संदर्भ
description: नोड का मूल मान वापस करता है।
type: docs
weight: 53
url: /hi/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() मेथड


नोड का मूल मान वापस करता है।

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### वापसी मान

नोड का मूल मान। यह मेथड **nullptr** लौटाता है यदि नोड न तो एट्रीब्यूट है और न ही टेक्स्ट नोड, या यदि नोड को सम्मिलित किया जा रहा है। यदि इसे **XmlDocument::NodeChanging** इवेंट में कॉल किया जाता है, तो **get_OldValue** नोड का वर्तमान मान लौटाता है जिसे परिवर्तन सफल होने पर प्रतिस्थापित किया जाएगा। यदि इसे **XmlDocument::NodeChanged** इवेंट में कॉल किया जाता है, तो **get_OldValue** परिवर्तन से पहले नोड का मान लौटाता है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlNodeChangedEventArgs](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)