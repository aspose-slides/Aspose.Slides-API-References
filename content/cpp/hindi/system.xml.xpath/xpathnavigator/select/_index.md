---
title: Select()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XPath अभिव्यक्ति का उपयोग करके एक नोड सेट का चयन करता है।
type: docs
weight: 794
url: /hi/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) मेथड

निर्दिष्ट [XPath](../../) अभिव्यक्ति का उपयोग करके एक नोड सेट का चयन करता है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | एक [String](../../../system/string/) जो एक [XPath](../../) अभिव्यक्ति का प्रतिनिधित्व करता है। |

### Return Value

एक [XPathNodeIterator](../../xpathnodeiterator/) जो चयनित नोड सेट की ओर संकेत करता है।

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) मेथड

निर्दिष्ट [XPath](../../) अभिव्यक्ति और [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके नेमस्पेस प्रीफ़िक्स को हल करने के लिए एक नोड सेट का चयन करता है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | एक [String](../../../system/string/) जो एक [XPath](../../) अभिव्यक्ति का प्रतिनिधित्व करता है। |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट जो नेमस्पेस प्रीफ़िक्स को हल करने के लिए उपयोग किया जाता है। |

### Return Value

एक [XPathNodeIterator](../../xpathnodeiterator/) जो चयनित नोड सेट की ओर संकेत करता है।

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) मेथड

निर्दिष्ट [XPathExpression](../../xpathexpression/) का उपयोग करके एक नोड सेट का चयन करता है।

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | एक [XPathExpression](../../xpathexpression/) ऑब्जेक्ट जिसमें संकलित [XPath](../../) क्वेरी होती है। |

### Return Value

एक [XPathNodeIterator](../../xpathnodeiterator/) जो चयनित नोड सेट की ओर संकेत करता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XPathNodeIterator](../../xpathnodeiterator/)
* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* क्लास [XPathExpression](../../xpathexpression/)
* नामस्थान [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)