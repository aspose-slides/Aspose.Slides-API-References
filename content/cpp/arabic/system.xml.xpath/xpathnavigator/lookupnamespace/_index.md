---
title: LookupNamespace()
second_title: Aspose.Slides لمرجع API للغة C++
description: يُرجِع عنوان URI للمساحة الاسمية للبادئة المحددة.
type: docs
weight: 404
url: /ar/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) method

تُرجع عنوان URI للمساحة الاسمية للبادئة المحددة.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | البادئة التي تريد حل عنوان URI للمساحة الاسمية الخاصة بها. لمطابقة المساحة الاسمية الافتراضية، مرّر [String::Empty](../../../system/string/empty/). |

### قيمة الإرجاع

كائن [String](../../../system/string/) يحتوي على عنوان URI للمساحة الاسمية المعين للبادئة المحددة؛ **nullptr** إذا لم يتم تعيين عنوان URI للمساحة الاسمية للبادئة المحددة. الكائن [String](../../../system/string/) المرتجع مُذَكَّر.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XPathNavigator](../)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)