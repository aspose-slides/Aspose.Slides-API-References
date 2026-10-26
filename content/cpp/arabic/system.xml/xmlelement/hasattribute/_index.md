---
title: HasAttribute()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد ما إذا كانت العقدة الحالية تحتوي على سمة بالاسم المحدد.
type: docs
weight: 300
url: /ar/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) طريقة


يحدد ما إذا كانت العقدة الحالية تحتوي على سمة بالاسم المحدد.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم السمة المراد العثور عليها. هذا اسم مؤهل. يتم مطابقة هذا الاسم مع قيمة **get_Name** للعقدة المطابقة. |

### قيمة الإرجاع

**true** إذا كانت العقدة الحالية تحتوي على السمة المحددة؛ وإلا **false**.

## XmlElement::HasAttribute(String, String) طريقة


يحدد ما إذا كانت العقدة الحالية تحتوي على سمة بالاسم المحلي المحدد ومسار اسم المجال (URI).

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للسمة المراد العثور عليها. |
| namespaceURI | [String](../../../system/string/) | مسار اسم المجال (URI) للسمة المراد العثور عليها. |

### قيمة الإرجاع

**true** إذا كانت العقدة الحالية تحتوي على السمة المحددة؛ وإلا **false**.

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XmlElement](../)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)