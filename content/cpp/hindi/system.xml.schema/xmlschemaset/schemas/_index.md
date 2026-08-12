---
title: Schemas()
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlSchemaSet में सभी XML Schema definition language (XSD) स्कीमा का संग्रह लौटाता है।
type: docs
weight: 248
url: /hi/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


सभी XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा का संग्रह [XmlSchemaSet](../) में लौटाता है।

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### रिटर्न वैल्यू

एक IList ऑब्जेक्ट जिसमें सभी स्कीमा शामिल हैं जो [XmlSchemaSet](../) में जोड़े गए हैं। यदि [XmlSchemaSet](../) में कोई स्कीमा नहीं जोड़ा गया है, तो एक खाली संग्रह लौटाया जाता है।

## XmlSchemaSet::Schemas(String) method


सभी XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा का संग्रह [XmlSchemaSet](../) में लौटाता है जो दिए गए नेमस्पेस से संबंधित हैं।

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | स्कीमा की **targetNamespace** प्रॉपर्टी। |

### रिटर्न वैल्यू

एक IList ऑब्जेक्ट जिसमें सभी स्कीमा शामिल हैं जो [XmlSchemaSet](../) में जोड़े गए हैं और दिए गए नेमस्पेस से संबंधित हैं। यदि [XmlSchemaSet](../) में कोई स्कीमा नहीं जोड़ा गया है, तो एक खाली संग्रह लौटाया जाता है।

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IList](../../../system.collections.generic/ilist/)
* क्लास [XmlSchema](../../xmlschema/)
* क्लास [XmlSchemaSet](../)
* क्लास [List](../../../system.collections.generic/list/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)