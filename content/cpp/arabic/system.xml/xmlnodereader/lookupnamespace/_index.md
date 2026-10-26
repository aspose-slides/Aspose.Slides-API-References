---
title: LookupNamespace()
second_title: مرجع API Aspose.Slides للغة C++
description: يحل بادئة مساحة الاسم داخل نطاق العنصر الحالي.
type: docs
weight: 404
url: /ar/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) طريقة

يحّل بادئة مساحة الاسم في نطاق العنصر الحالي.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | البادئة التي تريد حل URI مساحة الاسم الخاصة بها. لمطابقة مساحة الاسم الافتراضية، مرّر سلسلة فارغة. لا يلزم أن تكون هذه السلسلة مُذرة. |

### قيمة الإرجاع

URI مساحة الاسم الذي تُطابقه البادئة أو **nullptr** إذا لم يتم العثور على بادئة مطابقة.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlNodeReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)