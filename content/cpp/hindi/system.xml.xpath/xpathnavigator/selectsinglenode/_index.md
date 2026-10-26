---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XPath क्वेरी का उपयोग करके XPathNavigator में एकल नोड का चयन करता है।
type: docs
weight: 781
url: /hi/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) विधि

निर्दिष्ट [XPath](../../) क्वेरी का उपयोग करके [XPathNavigator](../) में एकल नोड का चयन करता है।

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | एक [String](../../../system/string/) जो एक [XPath](../../) अभिव्यक्ति को दर्शाता है। |

### Return Value

एक [XPathNavigator](../) ऑब्जेक्ट जो निर्दिष्ट [XPath](../../) क्वेरी के लिए पहला मेल खाने वाला नोड रखता है; अन्यथा, यदि कोई क्वेरी परिणाम नहीं हैं तो **nullptr**।

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) विधि

निर्दिष्ट [XPath](../../) क्वेरी और [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके [XPathNavigator](../) वस्तु में एकल नोड का चयन करता है, जो नेमस्पेस उपसर्गों को हल करने के लिए निर्दिष्ट है।

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | एक [String](../../../system/string/) जो एक [XPath](../../) अभिव्यक्ति को दर्शाता है। |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट जिसका उपयोग [XPath](../../) क्वेरी में नेमस्पेस उपसर्गों को हल करने के लिए किया जाता है। |

### Return Value

एक [XPathNavigator](../) ऑब्जेक्ट जो निर्दिष्ट [XPath](../../) क्वेरी के लिए पहला मेल खाने वाला नोड रखता है; अन्यथा **nullptr** यदि कोई क्वेरी परिणाम नहीं हैं।

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) विधि

निर्दिष्ट [XPathExpression](../../xpathexpression/) ऑब्जेक्ट का उपयोग करके [XPathNavigator](../) में एकल नोड का चयन करता है।

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | एक [XPathExpression](../../xpathexpression/) ऑब्जेक्ट जिसमें संकलित [XPath](../../) क्वेरी होती है। |

### Return Value

एक [XPathNavigator](../) ऑब्जेक्ट जो निर्दिष्ट [XPath](../../) क्वेरी के लिए पहला मेल खाने वाला नोड रखता है; अन्यथा **nullptr** यदि कोई क्वेरी परिणाम नहीं हैं।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XPathNavigator](../)
* क्लास [String](../../../system/string/)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* क्लास [XPathExpression](../../xpathexpression/)
* नामस्थान [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)