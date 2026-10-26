---
title: GetAttribute()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد قيمة الخاصية التي لها الاسم المحلي ومسار URI للمساحة الاسمية المحددة.
type: docs
weight: 482
url: /ar/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) طريقة

تُرجِع قيمة الخاصية التي لها الاسم المحلي ومساحة الاسم المحددين.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية. **localName** حسّاس لحالة الأحرف. |
| namespaceURI | [String](../../../system/string/) | معرّف URI للمساحة الاسمية للخاصية. |

### قيمة الإرجاع

كائن [String](../../../system/string/) يحتوي على قيمة الخاصية المحددة؛ [String::Empty](../../../system/string/empty/) إذا لم يتم العثور على خاصية مطابقة، أو إذا لم يكن [XPathNavigator](../) موضعًا على عقدة عنصر.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XPathNavigator](../)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)