---
title: LookupNamespace()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يحلّ بادئة مساحة الاسم في نطاق العنصر الحالي.
type: docs
weight: 547
url: /ar/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) method

يحل محل بادئة مساحة الاسم في نطاق العنصر الحالي.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | البادئة التي تريد حل معرّف الموارد الموحد (URI) الخاص بها. لمطابقة نطاق الاسم الافتراضي، مرّر سلسلة فارغة. |

### قيمة الإرجاع

معرّف الموارد الموحد (URI) لمساحة الاسم التي تُطابق البادئة أو **nullptr** إذا لم يُعثر على بادئة مطابقة.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlValidatingReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)