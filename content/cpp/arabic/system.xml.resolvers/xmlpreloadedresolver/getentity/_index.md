---
title: GetEntity()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يقوم بربط URI بكائن يحتوي على المورد الفعلي.
type: docs
weight: 53
url: /ar/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) طريقة

يقوم بربط URI بكائن يحتوي على المورد الفعلي.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI الذي تم إرجاعه من استدعاء [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | حاليًا غير مستخدم. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع الكائن المراد إرجاعه. يدعم [XmlPreloadedResolver](../) كائنات Stream وكائنات TextReader للـ URIs التي أضيفت كـ [String](../../../system/string/). إذا لم يكن النوع المطلوب مدعومًا من قبل المُحَلِّ، فسيتم طرح استثناء. استخدم طريقة XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) لتحديد ما إذا كان **Type** معين مدعومًا من هذا المُحَلِّ. |

### قيمة الإرجاع

كائن Stream أو TextReader يتطابق مع المصدر الفعلي.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [XmlPreloadedResolver](../)
* مساحة اسم [System::Xml::Resolvers](../../)
* مكتبة [Aspose.Slides](../../../)