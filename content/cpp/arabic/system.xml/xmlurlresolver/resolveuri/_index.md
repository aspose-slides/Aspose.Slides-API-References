---
title: ResolveUri()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.
type: docs
weight: 66
url: /ar/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) طريقة

يحدد الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | الـ URI الأساسي المستخدم لتحديد الـ URI النسبي. |
| relativeUri | [String](../../../system/string/) | الـ URI المراد تحديده. يمكن أن يكون الـ URI مطلقًا أو نسبيًا. إذا كان مطلقًا، فإن هذه القيمة تستبدل قيمة **baseUri** فعليًا. إذا كان نسبيًا، فإنها تتحد مع **baseUri** لصنع URI مطلق. |

### قيمة الإرجاع

الـ URI المطلق، أو **nullptr** إذا تعذر تحديد الـ URI النسبي.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [XmlUrlResolver](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)