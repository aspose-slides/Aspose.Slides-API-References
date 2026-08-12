---
title: Contains()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह दर्शाता है कि क्या निर्दिष्ट लक्ष्य नेमस्पेस URI वाला XML Schema डिफिनिशन लैंग्वेज (XSD) स्कीमा XmlSchemaSet में है।
type: docs
weight: 196
url: /hi/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) मेथड

निर्देश देता है कि क्या निर्दिष्ट लक्ष्य नेमस्पेस URI वाला XML [Schema](../../) डिफिनिशन लैंग्वेज (XSD) स्कीमा [XmlSchemaSet](../) में है।

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | स्कीमा **targetNamespace** प्रॉपर्टी। |

### रिटर्न वैल्यू

**true** यदि निर्दिष्ट लक्ष्य नेमस्पेस URI वाला स्कीमा [XmlSchemaSet](../) में है; अन्यथा, **false**।

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) मेथड

निर्देश देता है कि क्या निर्दिष्ट XML [Schema](../../) डिफिनिशन लैंग्वेज (XSD) [XmlSchema](../../xmlschema/) ऑब्जेक्ट [XmlSchemaSet](../) में है।

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) ऑब्जेक्ट। |

### रिटर्न वैल्यू

**true** यदि [XmlSchema](../../xmlschema/) ऑब्जेक्ट [XmlSchemaSet](../) में है; अन्यथा, **false**।

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlSchema](../../xmlschema/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)