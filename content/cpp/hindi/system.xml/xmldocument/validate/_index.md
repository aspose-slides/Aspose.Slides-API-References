---
title: Validate()
second_title: Aspose.Slides for C++ API संदर्भ
description: "XmlDocument को XML Schema Definition Language (XSD) स्कीमा जो XmlDocument::get_Schemas सूची में हैं, के विरुद्ध वैध करता है।"
type: docs
weight: 573
url: /hi/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) विधि

[XmlDocument](../) को XML [Schema](../../../system.xml.schema/) Definition Language (XSD) स्कीमा जो [XmlDocument::get_Schemas](../get_schemas/) सूची में हैं, के विरुद्ध वैध करता है।

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) ऑब्जेक्ट जो स्कीमा वैधता चेतावनियों और त्रुटियों के बारे में जानकारी प्राप्त करता है। |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) विधि

निर्दिष्ट [XmlNode](../../xmlnode/) ऑब्जेक्ट को XML [Schema](../../../system.xml.schema/) Definition Language (XSD) स्कीमा जो [XmlDocument::get_Schemas](../get_schemas/) सूची में हैं, के विरुद्ध वैध करता है।

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) ऑब्जेक्ट जो स्कीमा वैधता चेतावनियों और त्रुटियों के बारे में जानकारी प्राप्त करता है। |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) ऑब्जेक्ट जो [XmlDocument](../) से सत्यापन हेतु बनाया गया है। |

## देखें

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocument](../)
* Class [XmlNode](../../xmlnode/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)