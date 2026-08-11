---
title: Contains()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع قيمة تشير إلى ما إذا كان targetNamespace الخاص بـ XmlSchema المحدد موجودًا في المجموعة.
type: docs
weight: 66
url: /ar/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) طريقة


يرجع قيمة تُشير إلى ما إذا كان **targetNamespace** للـ [XmlSchema](../../xmlschema/) المحدد موجودًا في المجموعة.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | الكائن [XmlSchema](../../xmlschema/). |

### قيمة الإرجاع

**true** إذا كان هناك مخطط في المجموعة يحمل نفس **targetNamespace**؛ وإلا، **false**.

## XmlSchemaCollection::Contains(const String\&) طريقة


يرجع قيمة تُشير إلى ما إذا كان مخطط باسم مساحة الاسم المحددة موجودًا في المجموعة.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | معرف URI لمساحة الاسم المرتبط بالمخطط. بالنسبة لمخططات XML، سيكون عادةً مساحة الاسم الهدف. |

### قيمة الإرجاع

**true** إذا كان مخطط بالمساحة المحددة موجودًا في المجموعة؛ وإلا، **false**.

## انظر أيضا

* نوع معرف [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchema](../../xmlschema/)
* فئة [XmlSchemaCollection](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)