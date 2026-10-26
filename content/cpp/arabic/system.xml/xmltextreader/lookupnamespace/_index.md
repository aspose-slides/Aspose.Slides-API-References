---
title: LookupNamespace()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بحل بادئة مساحة الاسم في نطاق العنصر الحالي.
type: docs
weight: 612
url: /ar/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) طريقة


يُحَلّ مساحة الاسم للبادئة في نطاق العنصر الحالي.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | البادئة التي تريد حل مساحة الاسم URI الخاصة بها. لمطابقة مساحة الاسم الافتراضية، مرّر سلسلة فارغة. لا يلزم أن تكون هذه السلسلة مُذَكَّرة. |

### قيمة الإرجاع

عنوان URI لمساحة الاسم الذي تُطابقه البادئة أو **nullptr** إذا لم يتم العثور على بادئة مطابقة.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlTextReader](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)