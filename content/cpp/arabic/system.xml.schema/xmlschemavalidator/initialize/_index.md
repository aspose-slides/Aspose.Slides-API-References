---
title: Initialize()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بتهيئة حالة كائن XmlSchemaValidator.
type: docs
weight: 118
url: /ar/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() طريقة

يُهيئ حالة الكائن [XmlSchemaValidator](../).

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) طريقة

يُهيئ حالة الكائن [XmlSchemaValidator](../) باستخدام [XmlSchemaObject](../../xmlschemaobject/) المحدد للتحقق الجزئي.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### معلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | كائن [XmlSchemaElement](../../xmlschemaelement/) أو [XmlSchemaAttribute](../../xmlschemaattribute/) أو [XmlSchemaType](../../xmlschematype/) يُستخدم لتهيئة سياق التحقق من صحة الكائن [XmlSchemaValidator](../) للتحقق الجزئي. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchemaValidator](../)
* فئة [XmlSchemaObject](../../xmlschemaobject/)
* نطاق الاسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)