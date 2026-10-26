---
title: LookupNamespace()
second_title: مرجع API Aspose.Slides للغة C++
description: عند تجاوزها في فئة مشتقة، تحل بادئة مساحة الاسم في نطاق العنصر الحالي.
type: docs
weight: 729
url: /ar/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) method

When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | البادئة التي تريد حل URI مساحة الاسم الخاصة بها. لمطابقة مساحة الاسم الافتراضية، مرر سلسلة فارغة. |

### Return Value

URI مساحة الاسم التي تُطابقها البادئة أو **nullptr** إذا لم يتم العثور على بادئة مطابقة.

## See Also

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)