---
title: GetAttribute()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित स्थानीय नाम और नेमस्पेस URI वाले एट्रीब्यूट का मान लौटाता है।
type: docs
weight: 482
url: /hi/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) विधि

निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रीब्यूट का मान लौटाता है।

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### आर्ग्यूमेंट्स
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| localName | [String](../../../system/string/) | एट्रीब्यूट का स्थानीय नाम। **localName** केस-सेंसिटिव है। |
| namespaceURI | [String](../../../system/string/) | एट्रीब्यूट का नेमस्पेस URI। |

### रिटर्न मान
एक [String](../../../system/string/) जिसमें निर्दिष्ट एट्रीब्यूट का मान होता है; [String::Empty](../../../system/string/empty/) यदि मिलता हुआ एट्रीब्यूट नहीं मिला, या यदि [XPathNavigator](../) किसी एलिमेंट नोड पर स्थित नहीं है।

## देखें
* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)