---
title: ParseValue()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब एक व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट string को एक निर्मित या उपयोगकर्ता-परिभाषित सरल प्रकार के विरुद्ध मान्य करता है।
type: docs
weight: 53
url: /hi/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) विधि

जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट **string** को एक निर्मित या उपयोगकर्ता-परिभाषित सरल प्रकार के विरुद्ध मान्य किया जाता है।

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | [String](../../../system/string/) | सरल प्रकार के विरुद्ध **string** को मान्य करने के लिए। |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | जब यह [XmlSchemaDatatype](../) ऑब्जेक्ट **xs:NCName** प्रकार को दर्शाता है, तो **string** को पार्स करते समय एटमाइज़ेशन हेतु उपयोग किया जाने वाला [XmlNameTable](../../../system.xml/xmlnametable/)। |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | जब यह [XmlSchemaDatatype](../) ऑब्जेक्ट **xs:QName** प्रकार को दर्शाता है, तो **string** को पार्स करते समय उपयोग किया जाने वाला [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट। |

### वापसी मान

एक [Object](../../../system/object/) जिसे [XmlSchemaDatatype::get_ValueType](../get_valuetype/) कॉल द्वारा लौटाए गए प्रकार में सुरक्षित रूप से कास्ट किया जा सकता है।

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [String](../../../system/string/)
* क्लास [XmlNameTable](../../../system.xml/xmlnametable/)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* क्लास [XmlSchemaDatatype](../)
* नामस्थान [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)