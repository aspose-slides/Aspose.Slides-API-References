---
title: GetEntity()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بربط URI بجسم يحتوي على المورد الفعلي.
type: docs
weight: 53
url: /ar/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) طريقة

يقوم بربط URI بجسم يحتوي على المورد الفعلي.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان الـ URI الذي تم إرجاعه من استدعاء [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | حاليًا غير مستخدم. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع الكائن المراد إرجاعه. التنفيذ الحالي يُعيد فقط كائنات Stream. |

### قيمة الإرجاع

كائن تدفق أو **nullptr** إذا تم تحديد نوع غير التدفق.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [XmlUrlResolver](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)