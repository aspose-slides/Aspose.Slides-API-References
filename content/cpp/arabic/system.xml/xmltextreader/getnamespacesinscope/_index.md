---
title: GetNamespacesInScope()
second_title: Aspose.Slides لـ C++ مرجع API
description: تُرجِع مجموعة تحتوي على جميع مساحات الاسم الحالية ضمن النطاق.
type: docs
weight: 716
url: /ar/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) طريقة

تُرجِع مجموعة تحتوي على جميع مساحات الاسم الحالية ضمن النطاق.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### الوسائط

| معـامل | نوع | وصف |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | قيمة XmlNamespaceScope تحدد نوع عقد مساحات الاسم التي سيتم إرجاعها. |

### قيمة الإرجاع

كائن IDictionary يحتوي على جميع مساحات الاسم الحالية ضمن النطاق. إذا لم يكن القارئ مُوضَعًا على عنصر، سيتم إرجاع قاموس فارغ (بدون مساحات اسم).

## أنظر أيضًا

* تعداد [XmlNamespaceScope](../../xmlnamespacescope/)
* تعريف_نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDictionary](../../../system.collections.generic/idictionary/)
* فئة [String](../../../system/string/)
* فئة [XmlTextReader](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)