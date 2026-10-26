---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: दिए गए namespace URI से संबंधित XmlSchema को लौटाता है।
type: docs
weight: 53
url: /hi/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) विधि

दिए गए namespace URI से संबंधित [XmlSchema](../../xmlschema/) को लौटाता है।

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | आप जिस schema को लौटाना चाहते हैं, उसके साथ जुड़े namespace URI। यह आमतौर पर schema का **targetNamespace** होगा। |

### रिटर्न मान

namespace URI से संबंधित [XmlSchema](../../xmlschema/); यदि दिया गया namespace से जुड़ा लोडेड schema नहीं है या namespace XDR schema से जुड़ा है तो **nullptr**।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)