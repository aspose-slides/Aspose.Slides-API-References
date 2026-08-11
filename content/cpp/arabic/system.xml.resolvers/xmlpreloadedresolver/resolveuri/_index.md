---
title: ResolveUri()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.
type: docs
weight: 40
url: /ar/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) طريقة

يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | الـ URI الأساسي المستخدم لحل الـ URI النسبي. |
| relativeUri | [String](../../../system/string/) | الـ URI المراد حله. يمكن أن يكون الـ URI مطلقًا أو نسبيًا. إذا كان مطلقًا، فإن هذه القيمة تستبدل قيمة **baseUri** فعليًا. إذا كان نسبيًا، فإنه يُدمج مع **baseUri** لتكوين URI مطلق. |

### قيمة الإرجاع

الـ [Uri](../../../system/uri/) الذي يمثل الـ URI المطلق أو **nullptr** إذا تعذر حل الـ URI النسبي.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [XmlPreloadedResolver](../)
* مساحة الأسماء [System::Xml::Resolvers](../../)
* مكتبة [Aspose.Slides](../../../)