---
title: Initialize()
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlSchemaValidator ऑब्जेक्ट की स्थिति को प्रारम्भ करता है।
type: docs
weight: 118
url: /hi/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() विधि

[XmlSchemaValidator](../) ऑब्जेक्ट की स्थिति को प्रारम्भ करता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) विधि

[XmlSchemaValidator](../) ऑब्जेक्ट की स्थिति को आंशिक सत्यापन के लिये निर्दिष्ट [XmlSchemaObject](../../xmlschemaobject/) का उपयोग करके प्रारम्भ करता है।

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | एक [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) या [XmlSchemaType](../../xmlschematype/) ऑब्जेक्ट जिसका उपयोग [XmlSchemaValidator](../) ऑब्जेक्ट के वैधता संदर्भ को आंशिक सत्यापन के लिये प्रारम्भ करने में किया जाता है। |

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlSchemaValidator](../)
* क्लास [XmlSchemaObject](../../xmlschemaobject/)
* नामस्थान [System::Xml::Schema](../../)
* लाइब्रेरी [Aspose.Slides](../../../)