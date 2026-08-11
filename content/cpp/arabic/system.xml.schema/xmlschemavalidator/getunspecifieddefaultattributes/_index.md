---
title: GetUnspecifiedDefaultAttributes()
second_title: مرجع API ل Aspose.Slides للغة C++
description: "يتحقق من قيود الهوية على السمات الافتراضية ويملأ القائمة المحددة بكائنات XmlSchemaAttribute لأي سمات ذات قيم افتراضية لم يتم التحقق منها مسبقًا باستخدام طريقة XmlSchemaValidator::ValidateAttribute في سياق العنصر."
type: docs
weight: 157
url: /ar/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) طريقة

يتحقق من قيود الهوية على السمات الافتراضية ويملأ القائمة المحددة بكائنات [XmlSchemaAttribute](../../xmlschemaattribute/) لأي سمات ذات قيم افتراضية لم يتم التحقق منها مسبقًا باستخدام طريقة [XmlSchemaValidator::ValidateAttribute](../validateattribute/) في سياق العنصر.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | قائمة لتعبئتها بكائنات [XmlSchemaAttribute](../../xmlschemaattribute/) لأي سمات لم تُواجه بعد أثناء التحقق في سياق العنصر. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [List](../../../system.collections.generic/list/)
* فئة [Object](../../../system/object/)
* فئة [XmlSchemaValidator](../)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)