---
title: Reprocess()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XmlSchemaSet में पहले से मौजूद XML Schema definition language (XSD) स्कीमा को पुनः प्रोसेस करता है।
type: docs
weight: 222
url: /hi/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) मेथड

एक XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा को फिर से प्रोसेस करता है जो पहले से [XmlSchemaSet](../) में मौजूद है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | फिर से प्रोसेस करने के लिए स्कीमा। |

### रिटर्न वैल्यू

यदि स्कीमा मान्य है तो एक [XmlSchema](../../xmlschema/) ऑब्जेक्ट। यदि स्कीमा मान्य नहीं है और ValidationEventHandler निर्दिष्ट किया गया है, तो **nullptr** लौटाया जाता है और उपयुक्त वैलिडेशन इवेंट उठाया जाता है। अन्यथा, एक XmlSchemaException फेंका जाता है।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchema](../../xmlschema/)
* क्लास [XmlSchemaSet](../)
* नेमस्पेस [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)