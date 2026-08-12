---
title: Contains()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: निर्दिष्ट XmlSchema का targetNamespace संग्रह में है या नहीं, यह दर्शाने वाला मान लौटाता है।
type: docs
weight: 66
url: /hi/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) मेथड

निर्दिष्ट [XmlSchema](../../xmlschema/) का **targetNamespace** संग्रह में है या नहीं, यह दर्शाने वाला मान लौटाता है।

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | यह [XmlSchema](../../xmlschema/) वस्तु। |

### परिणाम मान

**true** यदि संग्रह में समान **targetNamespace** वाला स्कीमा मौजूद है; अन्यथा, **false**।

## XmlSchemaCollection::Contains(const String\&) मेथड

निर्दिष्ट नेमस्पेस वाले स्कीमा के संग्रह में मौजूद होने को दर्शाने वाला मान लौटाता है।

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | स्कीमा से संबद्ध नेमस्पेस URI। XML स्कीमा के लिए, यह आम तौर पर target namespace होगा। |

### परिणाम मान

**true** यदि निर्दिष्ट नेमस्पेस वाला स्कीमा संग्रह में है; अन्यथा, **false**।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchema](../../xmlschema/)
* क्लास [XmlSchemaCollection](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)