---
title: Schemas()
second_title: مرجع API لـ C++ Aspose.Slides
description: تعيد مجموعة تضم جميع مخططات لغة تعريف مخطط XML (XSD) في XmlSchemaSet.
type: docs
weight: 248
url: /ar/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() طريقة

تعيد مجموعة تضم جميع مخططات لغة تعريف XML [Schema](../../) (XSD) في [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### قيمة الإرجاع

كائن IList يحتوي على جميع المخططات التي تمت إضافتها إلى [XmlSchemaSet](../). إذا لم تتم إضافة أي مخططات إلى [XmlSchemaSet](../)، يتم إرجاع مجموعة فارغة.

## XmlSchemaSet::Schemas(String) طريقة

تعيد مجموعة تضم جميع مخططات لغة تعريف XML [Schema](../../) (XSD) في [XmlSchemaSet](../) التي تنتمي إلى نطاق الاسم المحدد.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | خاصية المخطط **targetNamespace**. |

### قيمة الإرجاع

كائن IList يحتوي على جميع المخططات التي تمت إضافتها إلى [XmlSchemaSet](../) والتي تنتمي إلى نطاق الاسم المحدد. إذا لم تتم إضافة أي مخططات إلى [XmlSchemaSet](../)، يتم إرجاع مجموعة فارغة.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IList](../../../system.collections.generic/ilist/)
* فئة [XmlSchema](../../xmlschema/)
* فئة [XmlSchemaSet](../)
* فئة [List](../../../system.collections.generic/list/)
* فئة [String](../../../system/string/)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)