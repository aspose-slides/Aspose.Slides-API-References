---
title: ValueAs()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: मान्य किए गए XML तत्व या विशेषता का मान, निर्दिष्ट प्रकार के अनुसार, नेमस्पेस प्रीफ़िक्स को हल करने के लिए निर्दिष्ट IXmlNamespaceResolver ऑब्जेक्ट का उपयोग करके लौटाता है।
type: docs
weight: 144
url: /hi/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) विधि

मान्य किए गए XML तत्व या विशेषता का मान, निर्दिष्ट प्रकार के अनुसार, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके, जो नेमस्पेस प्रीफ़िक्स को हल करने के लिए निर्दिष्ट किया गया है, लौटाता है।

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | मान्य किए गए XML तत्व या विशेषता का मान लौटाने के लिए उपयोग किया जाने वाला प्रकार। |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | नेमस्पेस प्रीफ़िक्स को हल करने के लिए उपयोग किया गया [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट। |

### वापसी मान

मान्य किए गए XML तत्व या विशेषता का मान अनुरोधित प्रकार के अनुसार।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)