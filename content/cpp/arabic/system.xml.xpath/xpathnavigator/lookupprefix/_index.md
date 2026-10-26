---
title: LookupPrefix()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تُرجِع البادئة المُعلن عنها للـ namespace URI المحدد.
type: docs
weight: 417
url: /ar/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String&) طريقة

تُرجِع البادئة المُعلن عنها للـ namespace URI المحدد.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | الـ namespace URI المطلوب حله للحصول على البادئة. |

### قيمة الإرجاع

كائن [String](../../../system/string/) يحتوي على بادئة مساحة الاسم المعينة للـ namespace URI المحدد؛ وإلا، [String::Empty](../../../system/string/empty/) إذا لم يتم تعيين بادئة للـ namespace URI المحدد. الـ [String](../../../system/string/) المرتجع هو مُذَكَّر.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XPathNavigator](../)
* مساحة الاسم [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)