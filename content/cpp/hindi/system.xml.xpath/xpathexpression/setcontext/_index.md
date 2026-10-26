---
title: SetContext()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो नेमस्पेस समाधान के लिए उपयोग किए जाने वाले XmlNamespaceManager ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
weight: 53
url: /hi/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) विधि

जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) ऑब्जेक्ट का उपयोग नेमस्पेस समाधान के लिए किया जाता है।

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | नेमस्पेस समाधान के लिए उपयोग होने वाला [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) ऑब्जेक्ट। |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) विधि

जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग नेमस्पेस समाधान के लिए किया जाता है।

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | एक ऑब्जेक्ट जो [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) इंटरफ़ेस को लागू करता है और नेमस्पेस समाधान के लिए उपयोग किया जाता है। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* क्लास [XPathExpression](../)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* नेमस्पेस [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)