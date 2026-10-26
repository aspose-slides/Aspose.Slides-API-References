---
title: ReadElementContentAsObject()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يقرأ العنصر الحالي ويعيد المحتوى ككائن.
type: docs
weight: 469
url: /ar/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() طريقة

يقرأ العنصر الحالي ويعيد المحتوى كـ [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### قيمة الإرجاع

كائن معبأ من النوع الأنسب. تحدد قيمة [XmlReader::get_ValueType](../get_valuetype/) النوع المناسب. إذا كان المحتوى مكتوبًا كنوع قائمة، فإن هذه الطريقة تُرجع مصفوفة من الكائنات المعبأة من النوع المناسب.

## XmlReader::ReadElementContentAsObject(String, String) طريقة

يتحقق من أن الاسم المحلي المحدد ومسار URI للنطاق يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كـ [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### الوسائط

| معاملة | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر. |
| namespaceURI | [String](../../../system/string/) | مسار URI للنطاق للعنصر. |

### قيمة الإرجاع

كائن معبأ من النوع الأنسب. تحدد قيمة [XmlReader::get_ValueType](../get_valuetype/) النوع المناسب. إذا كان المحتوى مكتوبًا كنوع قائمة، فإن هذه الطريقة تُرجع مصفوفة من الكائنات المعبأة من النوع المناسب.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [XmlReader](../)
* فئة [String](../../../system/string/)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)