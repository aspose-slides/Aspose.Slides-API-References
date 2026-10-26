---
title: CreateAttribute()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بإنشاء عقدة سمة على عقدة العنصر الحالية باستخدام بادئة مساحة الاسم والاسم المحلي ومساحة اسم URI المحددة مع القيمة المحددة.
type: docs
weight: 1041
url: /ar/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) طريقة

يُنشئ عقدة سمة على عقدة العنصر الحالية باستخدام بادئة مساحة الاسم والاسم المحلي ومساحة اسم URI المحددة مع القيمة المحددة.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | بادئة مساحة الاسم لعقدة السمة الجديدة (إن وجدت). |
| localName | [String](../../../system/string/) | الاسم المحلي لعقدة السمة الجديدة والذي لا يمكن [String::Empty](../../../system/string/empty/) أو **nullptr**. |
| namespaceURI | [String](../../../system/string/) | مساحة اسم URI لعقدة السمة الجديدة (إن وجدت). |
| value | [String](../../../system/string/) | قيمة عقدة السمة الجديدة. إذا تم تمرير [String::Empty](../../../system/string/empty/) أو **nullptr**، يتم إنشاء عقدة سمة فارغة. |

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XPathNavigator](../)
* مساحة الاسم [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)