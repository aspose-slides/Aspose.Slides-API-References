---
title: ValueAs()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान नोड का मान निर्दिष्ट Type के अनुसार लौटाता है, नेमस्पेस प्रीफ़िक्स को हल करने के लिए निर्दिष्ट IXmlNamespaceResolver ऑब्जेक्ट का उपयोग करके।
type: docs
weight: 378
url: /hi/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) विधि

वर्तमान नोड का मान निर्दिष्ट Type के अनुसार लौटाता है, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके नेमस्पेस प्रीफ़िक्स को हल करने के लिए।

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | वर्तमान नोड का मान जिस Type के रूप में लौटाना है। |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट जिसका उपयोग नेमस्पेस प्रीफ़िक्स को हल करने के लिए किया जाता है। |

### रिटर्न मान

वर्तमान नोड का मान अनुरोधित Type के रूप में।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* क्लास [XPathNavigator](../)
* नेमस्पेस [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)