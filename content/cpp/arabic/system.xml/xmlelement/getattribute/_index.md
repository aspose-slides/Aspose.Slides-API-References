---
title: GetAttribute()
second_title: Aspose.Slides ل C++ مرجع API
description: يرجع القيمة للخاصية ذات الاسم المحدد.
type: docs
weight: 209
url: /ar/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) طريقة

يرجع القيمة للخاصية ذات الاسم المحدد.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم الخاصية المراد استرجاعها. هذا اسم مؤهل. يتم مطابقته مع قيمة **get_Name** للعنصر المطابق. |

### قيمة الإرجاع

قيمة الخاصية المحددة. يتم إرجاع سلسلة فارغة إذا لم يُعثر على خاصية مطابقة أو إذا لم يكن للخاصية قيمة محددة أو افتراضية.

## XmlElement::GetAttribute(String, String) طريقة

يرجع القيمة للخاصية التي لها الاسم المحلي المحدد ومعرّف مساحة الاسم.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للخاصية المراد استرجاعها. |
| namespaceURI | [String](../../../system/string/) | معرّف مساحة الاسم للخاصية المراد استرجاعها. |

### قيمة الإرجاع

قيمة الخاصية المحددة. يتم إرجاع سلسلة فارغة إذا لم يُعثر على خاصية مطابقة أو إذا لم يكن للخاصية قيمة محددة أو افتراضية.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlElement](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)