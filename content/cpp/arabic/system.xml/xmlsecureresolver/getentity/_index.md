---
title: GetEntity()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يقوم بربط URI بكائن يحتوي على المورد الفعلي.
type: docs
weight: 27
url: /ar/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) طريقة

يقوم بربط URI بكائن يحتوي على المورد الفعلي.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI الذي يتم إرجاعه من استدعاء [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | غير مستخدم حالياً. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | نوع الكائن الذي سيتم إرجاعه. الإصدار الحالي يُعيد فقط كائنات Stream. |

### قيمة الإرجاع

الدفق المُرجع عند استدعاء **GetEntity** على الـ [XmlResolver](../../xmlresolver/) الأساسي. إذا تم تحديد نوع غير Stream، فإن الطريقة تُعيد **nullptr**.

## أنظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [XmlSecureResolver](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)