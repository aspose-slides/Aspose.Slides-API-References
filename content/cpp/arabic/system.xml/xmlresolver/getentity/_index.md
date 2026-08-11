---
title: GetEntity()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزه في فئة مشتقة، يربط URI بكائن يحتوي على المورد الفعلي.
type: docs
weight: 14
url: /ar/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) طريقة


عند تجاوزه في فئة مشتقة، يقوم بربط URI بكائن يحتوي على المورد الفعلي.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | المعرف الموحد المرجع (URI) الذي تم إرجاعه من استدعاء [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | غير مستخدم حاليًا. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع الكائن المراد إرجاعه. الإصدار الحالي يرجع كائنات Stream فقط. |

### قيمة الإرجاع

كائن تدفق أو **nullptr** إذا تم تحديد نوع غير التدفق.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [Object](../../../system/object/)
* الفئة [Uri](../../../system/uri/)
* الفئة [String](../../../system/string/)
* الفئة [TypeInfo](../../../system/typeinfo/)
* الفئة [XmlResolver](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)