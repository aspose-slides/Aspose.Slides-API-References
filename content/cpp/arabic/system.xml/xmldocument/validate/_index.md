---
title: Validate()
second_title: Aspose.Slides للـ C++ مرجع API
description: "يتحقق من صحة XmlDocument مقابل لغة تعريف مخطط XML (XSD) الموجودة في قائمة XmlDocument::get_Schemas."
type: docs
weight: 573
url: /ar/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) طريقة


يقوم بالتحقق من [XmlDocument](../) ضد مخططات XML [Schema](../../../system.xml.schema/) Definition Language (XSD) الموجودة في قائمة [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | الكائن [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) الذي يتلقى معلومات حول تحذيرات وأخطاء التحقق من المخطط. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) طريقة


يقوم بالتحقق من الكائن [XmlNode](../../xmlnode/) المحدد ضد مخططات XML [Schema](../../../system.xml.schema/) Definition Language (XSD) الموجودة في قائمة [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | الكائن [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) الذي يتلقى معلومات حول تحذيرات وأخطاء التحقق من المخطط. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | الكائن [XmlNode](../../xmlnode/) الذي تم إنشاؤه من [XmlDocument](../) للتحقق. |

## انظر أيضًا

* تعريف نوع [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlDocument](../)
* فئة [XmlNode](../../xmlnode/)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)