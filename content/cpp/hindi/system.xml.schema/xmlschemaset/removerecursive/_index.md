---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट XML Schema परिभाषा भाषा (XSD) स्कीमा और सभी स्कीमा जिन्हें यह XmlSchemaSet से आयात करता है, हटाता है।
type: docs
weight: 183
url: /hi/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) विधि

निर्दिष्ट XML [Schema](../../) परिभाषा भाषा (XSD) स्कीमा और सभी स्कीमा जिन्हें यह आयात करता है, [XmlSchemaSet](../) से हटाता है।

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchemaSet](../) से हटाने के लिये [XmlSchema](../../xmlschema/) ऑब्जेक्ट। |

### वापसी मान

**true** यदि [XmlSchema](../../xmlschema/) ऑब्जेक्ट और उसके सभी आयात सफलतापूर्वक हटाए गए हों; अन्यथा, **false**।

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)