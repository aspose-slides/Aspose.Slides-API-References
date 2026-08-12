---
title: ValueAs()
second_title: Aspose.Slides for C++ API संदर्भ
description: आइटम का मान निर्दिष्ट प्रकार के रूप में लौटाता है।
type: docs
weight: 131
url: /hi/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) विधि


निर्दिष्ट प्रकार के रूप में आइटम का मान लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | आइटम मान को लौटाने के लिए प्रकार। |

### वापसी मान

आइटम का मान अनुरोधित प्रकार के रूप में।

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) विधि


जब किसी व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो नेमस्पेस उपसर्गों को हल करने के लिए निर्दिष्ट [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) वस्तु का उपयोग करके निर्दिष्ट प्रकार के रूप में आइटम का मान लौटाता है।

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | आइटम मान को लौटाने के लिए प्रकार। |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | नेमस्पेस उपसर्गों को हल करने के लिए उपयोग की गई [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) वस्तु। |

### वापसी मान

आइटम का मान अनुरोधित प्रकार के रूप में।

## संदर्भ देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)