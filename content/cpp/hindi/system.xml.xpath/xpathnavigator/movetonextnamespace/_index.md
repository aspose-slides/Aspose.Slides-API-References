---
title: MoveToNextNamespace()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट XPathNamespaceScope से मेल खाने वाले अगले नेमस्पेस नोड पर XPathNavigator को ले जाता है।
type: docs
weight: 573
url: /hi/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) method


जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](../) को निर्दिष्ट XPathNamespaceScope से मेल खाने वाले अगले नेमस्पेस नोड पर ले जाता है।

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | एक XPathNamespaceScope मान जो नेमस्पेस स्कोप का वर्णन करता है। |

### Return Value

**true** यदि [XPathNavigator](../) सफलतापूर्वक अगले नेमस्पेस नोड पर जाता है; अन्यथा, **false**। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## XPathNavigator::MoveToNextNamespace() method


[XPathNavigator](../) को अगले नेमस्पेस नोड पर ले जाता है।

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### Return Value

**true** यदि [XPathNavigator](../) सफलतापूर्वक अगले नेमस्पेस नोड पर जाता है; अन्यथा, **false**। यदि **false**, तो [XPathNavigator](../) की स्थिति अपरिवर्तित रहती है।

## See Also

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)