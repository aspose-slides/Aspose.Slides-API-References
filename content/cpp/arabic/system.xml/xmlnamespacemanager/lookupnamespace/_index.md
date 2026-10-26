---
title: LookupNamespace()
second_title: مرجع API Aspose.Slides للـ C++
description: يرجع URI مساحة الاسم للمقدمة المحددة.
type: docs
weight: 118
url: /ar/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) طريقة

يرجع URI مساحة الاسم للمقدمة المحددة.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | المقدمة التي تريد حل URI مساحة الاسم لها. لمطابقة مساحة الاسم الافتراضية، مرّر [String::Empty](../../../system/string/empty/). |

### قيمة الإرجاع

URI مساحة الاسم لـ **prefix** أو **nullptr** إذا لم تكن هناك مساحة اسم مرتبطة. السلسلة المُرجعة مُذرة. لمزيد من المعلومات حول السلاسل المُذرة، راجع الفئة [XmlNameTable](../../xmlnametable/).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNamespaceManager](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)