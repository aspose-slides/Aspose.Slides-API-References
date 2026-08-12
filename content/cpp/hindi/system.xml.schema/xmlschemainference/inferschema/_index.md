---
title: InferSchema()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XmlReader ऑब्जेक्ट में सम्मिलित XML दस्तावेज़ से XML Schema Definition Language (XSD) स्कीमा का अनुमान लगाता है।
type: docs
weight: 66
url: /hi/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method

XML [Schema](../../) Definition Language (XSD) स्कीमा को [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट में सम्मिलित XML दस्तावेज़ से निकाला जाता है।

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | एक [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट जिसमें XML दस्तावेज़ होता है जिससे स्कीमा निकाला जाता है। |

### Return Value

एक [XmlSchemaSet](../../xmlschemaset/) ऑब्जेक्ट जिसमें निकाले गए स्कीमा होते हैं।

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method

XML [Schema](../../) Definition Language (XSD) स्कीमा को [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट में सम्मिलित XML दस्तावेज़ से निकाला जाता है, और समान लक्ष्य नेमस्पेस वाले [XmlSchemaSet](../../xmlschemaset/) ऑब्जेक्ट में मौजूद मौजूदा स्कीमा का उपयोग करके निकाले गए स्कीमा को परिष्कृत किया जाता है।

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | एक [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट जिसमें XML दस्तावेज़ होता है जिससे स्कीमा निकाला जाता है। |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | एक [XmlSchemaSet](../../xmlschemaset/) ऑब्जेक्ट जिसमें मौजूद स्कीमा होता है जिसे निकाले गए स्कीमा को परिष्कृत करने के लिए उपयोग किया जाता है। |

### Return Value

एक [XmlSchemaSet](../../xmlschemaset/) ऑब्जेक्ट जिसमें निकाले गए स्कीमा होते हैं।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchemaSet](../../xmlschemaset/)
* क्लास [XmlReader](../../../system.xml/xmlreader/)
* क्लास [XmlSchemaInference](../)
* नामस्थान [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)