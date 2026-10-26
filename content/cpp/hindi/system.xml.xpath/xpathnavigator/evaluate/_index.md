---
title: Evaluate()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित XPath अभिव्यक्ति का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है।
type: docs
weight: 807
url: /hi/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) विधि

निर्दिष्ट [XPath](../../) अभिव्यक्ति का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | एक स्ट्रिंग जो एक [XPath](../../) अभिव्यक्ति का प्रतिनिधित्व करती है जिसे मूल्यांकित किया जा सकता है। |

### रिटर्न मान

अभिव्यक्ति का परिणाम ([Boolean](../../../system/boolean/), संख्या, स्ट्रिंग, या नोड सेट)। यह क्रमशः [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), या [XPathNodeIterator](../../xpathnodeiterator/) ऑब्जेक्ट्स से मेल खाता है।

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) विधि

निर्दिष्ट [XPath](../../) अभिव्यक्ति का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है, जिसमें [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग किया जाता है जो [XPath](../../) अभिव्यक्ति में नेमस्पेस प्रीफ़िक्स को हल करने के लिए निर्दिष्ट किया गया है।

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | एक स्ट्रिंग जो एक [XPath](../../) अभिव्यक्ति का प्रतिनिधित्व करती है जिसे मूल्यांकित किया जा सकता है। |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट जो [XPath](../../) अभिव्यक्ति में नेमस्पेस प्रीफ़िक्स को हल करने के लिए उपयोग किया जाता है। |

### रिटर्न मान

अभिव्यक्ति का परिणाम ([Boolean](../../../system/boolean/), संख्या, स्ट्रिंग, या नोड सेट)। यह क्रमशः [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), या [XPathNodeIterator](../../xpathnodeiterator/) ऑब्जेक्ट्स से मेल खाता है।

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) विधि

[XPathExpression](../../xpathexpression/) का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | एक [XPathExpression](../../xpathexpression/) जिसे मूल्यांकित किया जा सकता है। |

### रिटर्न मान

अभिव्यक्ति का परिणाम ([Boolean](../../../system/boolean/), संख्या, स्ट्रिंग, या नोड सेट)। यह क्रमशः [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), या [XPathNodeIterator](../../xpathnodeiterator/) ऑब्जेक्ट्स से मेल खाता है।

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) विधि

प्रदत्त कॉन्टेक्स्ट का उपयोग करके [XPathExpression](../../xpathexpression/) का मूल्यांकन करता है, और टाइप्ड परिणाम लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | एक [XPathExpression](../../xpathexpression/) जिसे मूल्यांकित किया जा सकता है। |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | एक [XPathNodeIterator](../../xpathnodeiterator/) जो चयनित नोड सेट की ओर संकेत करता है जिस पर मूल्यांकन किया जाना है। |

### रिटर्न मान

अभिव्यक्ति का परिणाम ([Boolean](../../../system/boolean/), संख्या, स्ट्रिंग, या नोड सेट)। यह क्रमशः [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), या [XPathNodeIterator](../../xpathnodeiterator/) ऑब्जेक्ट्स से मेल खाता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [String](../../../system/string/)
* क्लास [XPathNavigator](../)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* क्लास [XPathExpression](../../xpathexpression/)
* क्लास [XPathNodeIterator](../../xpathnodeiterator/)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)