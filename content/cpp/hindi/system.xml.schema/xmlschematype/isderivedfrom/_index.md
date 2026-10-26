---
title: IsDerivedFrom()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट व्युत्पन्न स्कीमा प्रकार आधार स्कीमा प्रकार से व्युत्पन्न है या नहीं, यह दर्शाने वाला मान लौटाता है।
type: docs
weight: 209
url: /hi/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) विधि

निर्दिष्ट व्युत्पन्न स्कीमा प्रकार आधार स्कीमा प्रकार से व्युत्पन्न है या नहीं, यह दर्शाने वाला मान लौटाता है।

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | परीक्षण के लिए व्युत्पन्न [XmlSchemaType](../)। |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | व्युत्पन्न [XmlSchemaType](../) का परीक्षण करने के लिए मूल [XmlSchemaType](../)। |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | परीक्षण से बाहर रखने के लिए प्रकार व्युत्पन्न विधि दर्शाने वाले XmlSchemaDerivationMethod मूल्यों में से एक। |

### Return Value

**true** यदि व्युत्पन्न प्रकार मूल प्रकार से व्युत्पन्न है; अन्यथा, **false**।

## See Also

* एन्युम [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* टाइपडैफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchemaType](../)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)