---
title: Compile()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट XPath अभिव्यक्ति को संकलित करता है और XPath अभिव्यक्ति का प्रतिनिधित्व करने वाला XPathExpression ऑब्जेक्ट लौटाता है।
type: docs
weight: 66
url: /hi/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method

निर्दिष्ट [XPath](../../) अभिव्यक्ति को संकलित करता है और [XPath](../../) अभिव्यक्ति का प्रतिनिधित्व करने वाला [XPathExpression](../) ऑब्जेक्ट लौटाता है।

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | एक [XPath](../../) अभिव्यक्ति। |

### वापसी मान

एक [XPathExpression](../) ऑब्जेक्ट।

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method

निर्दिष्ट [XPath](../../) अभिव्यक्ति को संकलित करता है, नामस्थान समाधान के लिए निर्दिष्ट [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट के साथ, और [XPath](../../) अभिव्यक्ति का प्रतिनिधित्व करने वाला [XPathExpression](../) ऑब्जेक्ट लौटाता है।

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | एक [XPath](../../) अभिव्यक्ति। |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | नामस्थान समाधान के लिए [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) इंटरफ़ेस को लागू करने वाला एक ऑब्जेक्ट। |

### वापसी मान

एक [XPathExpression](../) ऑब्जेक्ट।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)