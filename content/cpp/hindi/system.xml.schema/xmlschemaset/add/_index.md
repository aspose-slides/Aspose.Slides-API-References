---
title: Add()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट URL पर XML स्कीमा परिभाषा भाषा (XSD) स्कीमा को XmlSchemaSet में जोड़ता है।
type: docs
weight: 157
url: /hi/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) विधि


निर्दिष्ट URL पर XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा को [XmlSchemaSet](../) में जोड़ता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Arguments

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | स्कीमा का **targetNamespace** मान, या स्कीमा में निर्दिष्ट **targetNamespace** उपयोग करने के लिए **nullptr**। |
| schemaUri | const [String](../../../system/string/)\& | उस URL को जो लोड करने के लिए स्कीमा निर्दिष्ट करता है। |

### Return Value

यदि स्कीमा वैध है तो [XmlSchema](../../xmlschema/) ऑब्जेक्ट लौटाता है। यदि स्कीमा वैध नहीं है और ValidationEventHandler निर्दिष्ट किया गया है, तो **nullptr** लौटाया जाता है और उपयुक्त मान्यकरण इवेंट उठाया जाता है। अन्यथा, एक XmlSchemaException फेंका जाता है।

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) विधि


XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा को [XmlReader](../../../system.xml/xmlreader/) में निहित [XmlSchemaSet](../) में जोड़ता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Arguments

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | स्कीमा का **targetNamespace** मान, या स्कीमा में निर्दिष्ट **targetNamespace** उपयोग करने के लिए **nullptr**। |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ऑब्जेक्ट। |

### Return Value

यदि स्कीमा वैध है तो [XmlSchema](../../xmlschema/) ऑब्जेक्ट लौटाता है। यदि स्कीमा वैध नहीं है और ValidationEventHandler निर्दिष्ट किया गया है, तो **nullptr** लौटाया जाता है और उपयुक्त मान्यकरण इवेंट उठाया जाता है। अन्यथा, एक XmlSchemaException फेंका जाता है।

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) विधि


दिए गए [XmlSchemaSet](../) में सभी XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा को [XmlSchemaSet](../) में जोड़ता है।

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Arguments

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | [XmlSchemaSet](../) ऑब्जेक्ट। |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) विधि


दिए गए [XmlSchema](../../xmlschema/) को [XmlSchemaSet](../) में जोड़ता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) ऑब्जेक्ट को [XmlSchemaSet](../) में जोड़ने के लिए। |

### Return Value

यदि स्कीमा वैध है तो [XmlSchema](../../xmlschema/) ऑब्जेक्ट लौटाता है। यदि स्कीमा वैध नहीं है और ValidationEventHandler निर्दिष्ट किया गया है, तो **nullptr** लौटाया जाता है और उपयुक्त मान्यकरण इवेंट उठाया जाता है। अन्यथा, एक XmlSchemaException फेंका जाता है।

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)