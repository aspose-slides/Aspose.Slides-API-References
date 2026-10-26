---
title: ChangeType()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मान को बदलता है, जिसका प्रकार XML स्कीमा प्रकार XmlSchemaDatatype द्वारा प्रतिनिधित्व किए गए वैध प्रतिनिधित्वों में से एक है, निर्दिष्ट रन-टाइम प्रकार में।
type: docs
weight: 66
url: /hi/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) मेथड


निर्दिष्ट मान को बदलता है, जिसका प्रकार XML स्कीमा प्रकार [XmlSchemaDatatype](../) द्वारा प्रतिनिधित्व किए गए वैध प्रतिनिधित्वों में से एक है, निर्दिष्ट रन-टाइम प्रकार में।

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | निर्दिष्ट प्रकार में बदलने के लिये इनपुट मान। |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | इनपुट मान को बदलने के लिये लक्ष्य प्रकार। |

### रिटर्न वैल्यू

परिवर्तित इनपुट मान।

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) मेथड


निर्दिष्ट मान को बदलता है, जिसका प्रकार XML स्कीमा प्रकार [XmlSchemaDatatype](../) द्वारा प्रतिनिधित्व किए गए वैध प्रतिनिधित्वों में से एक है, यदि [XmlSchemaDatatype](../) **xs:QName** प्रकार को दर्शाता है या उससे व्युत्पन्न किसी प्रकार को, तो [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) का उपयोग करके निर्दिष्ट रन-टाइम प्रकार में।

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | निर्दिष्ट प्रकार में बदलने के लिये इनपुट मान। |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | इनपुट मान को बदलने के लिये लक्ष्य प्रकार। |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | एक [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) जिसका उपयोग नेमस्पेस उपसर्गों को हल करने के लिये किया जाता है। यह केवल तब उपयोगी है जब [XmlSchemaDatatype](../) **xs:QName** प्रकार को दर्शाता है या उससे व्युत्पन्न किसी प्रकार को। |

### रिटर्न वैल्यू

परिवर्तित इनपुट मान।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [XmlSchemaDatatype](../)
* क्लास [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)