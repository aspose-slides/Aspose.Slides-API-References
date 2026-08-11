---
title: ResolveUri()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تقوم بحل URI المطلق من URI الأساسي والنسبي.
type: docs
weight: 27
url: /ar/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) الطريقة

عند تجاوزها في فئة مشتقة، تقوم بحل URI المطلق من URI الأساسي والنسبي.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI الأساسي المستخدم لحل URI النسبي. |
| relativeUri | [String](../../../system/string/) | URI المراد حله. يمكن أن يكون الـ URI مطلقًا أو نسبيًا. إذا كان مطلقًا، فإن هذه القيمة تستبدل قيمة **baseUri** فعليًا. إذا كان نسبيًا، فإنه يُدمج مع **baseUri** لتكوين URI مطلق. |

### قيمة الإرجاع

URI المطلق أو **nullptr** إذا تعذّر حل URI النسبي.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [XmlResolver](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)