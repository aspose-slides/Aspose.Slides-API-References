---
title: MoveToFirstNamespace()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो XPathNavigator को निर्दिष्ट XPathNamespaceScope से मेल खाने वाले प्रथम नेमस्पेस नोड की ओर ले जाता है।
type: docs
weight: 560
url: /hi/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) विधि

जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](../) को XPathNamespaceScope द्वारा निर्दिष्ट प्रथम नेमस्पेस नोड की ओर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | एक XPathNamespaceScope मान जो नेमस्पेस स्कोप का वर्णन करता है। |

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) प्रथम नेमस्पेस नोड की ओर सफलतापूर्वक जाता है; अन्यथा, **false**। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## XPathNavigator::MoveToFirstNamespace() विधि

वर्तमान नोड के प्रथम नेमस्पेस नोड की ओर [XPathNavigator](../) को ले जाता है।

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### रिटर्न वैल्यू

**true** यदि [XPathNavigator](../) प्रथम नेमस्पेस नोड की ओर सफलतापूर्वक जाता है; अन्यथा, **false**। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## संबंधित देखें

* एनम [XPathNamespaceScope](../../xpathnamespacescope/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)