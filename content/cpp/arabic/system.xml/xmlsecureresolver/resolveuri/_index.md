---
title: ResolveUri()
second_title: Aspose.Slides للغة C++ – مرجع API
description: يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي عن طريق استدعاء ResolveUri على الـ XmlResolver الأساسي.
type: docs
weight: 40
url: /ar/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) طريقة

يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي عن طريق استدعاء **ResolveUri** على الـ [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | الـ baseUri المستخدم لحل الـ relativeUri. |
| relativeUri | [String](../../../system/string/) | الـ URI المراد حله. يمكن أن يكون الـ URI مطلقًا أو نسبيًا. إذا كان مطلقًا، فستستبدل هذه القيمة قيمة **baseUri** فعليًا. إذا كان نسبيًا، فإنه يدمج مع **baseUri** لتكوين URI مطلق. |

### قيمة الإرجاع

الـ URI المطلق أو **nullptr** إذا لم يتمكن من حل الـ URI النسبي (يُعاد بواسطة استدعاء **ResolveUri** على الـ [XmlResolver](../../xmlresolver/) الأساسي).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [XmlSecureResolver](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)