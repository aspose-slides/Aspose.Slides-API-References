---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक XmlSchemaSimpleType लौटाता है जो क्वालिफ़ाइड नाम द्वारा निर्दिष्ट सरल प्रकार के निर्मित-इनबिल्ट सरल प्रकार को दर्शाता है।
type: docs
weight: 183
url: /hi/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) विधि

एक [XmlSchemaSimpleType](../../xmlschemasimpletype/) लौटाता है जो क्वालिफ़ाइड नाम द्वारा निर्दिष्ट किए गए सरल प्रकार का निर्मित-इनबिल्ट सरल प्रकार दर्शाता है।

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | सरल प्रकार का [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)। |

### वापसी मान

निर्मित-इनबिल्ट सरल प्रकार का प्रतिनिधित्व करने वाला [XmlSchemaSimpleType](../../xmlschemasimpletype/)।

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) विधि

एक [XmlSchemaSimpleType](../../xmlschemasimpletype/) लौटाता है जो निर्दिष्ट सरल प्रकार के निर्मित-इनबिल्ट सरल प्रकार को दर्शाता है।

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | सरल प्रकार को दर्शाने वाले XmlTypeCode मानों में से एक। |

### वापसी मान

निर्मित-इनबिल्ट सरल प्रकार का प्रतिनिधित्व करने वाला [XmlSchemaSimpleType](../../xmlschemasimpletype/)।

## संबंधित देखें

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Class [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)