---
title: Contains()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كان مخطط XML Schema definition language (XSD) مع مساحة الاسم المستهدفة المحددة موجودًا في XmlSchemaSet.
type: docs
weight: 196
url: /ar/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) طريقة

يحدد ما إذا كان مخطط XML [Schema](../../) للغة التعريف (XSD) مع مساحة الاسم المستهدفة المحددة موجودًا في [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | خاصية **targetNamespace** للمخطط. |

### قيمة الإرجاع

**true** إذا كان مخطط مع مساحة الاسم المستهدفة المحددة موجودًا في [XmlSchemaSet](../)؛ وإلا، **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) طريقة

يحدد ما إذا كان كائن XML [Schema](../../) تعريف اللغة (XSD) [XmlSchema](../../xmlschema/) المحدد موجودًا في [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | الكائن [XmlSchema](../../xmlschema/). |

### قيمة الإرجاع

**true** إذا كان الكائن [XmlSchema](../../xmlschema/) موجودًا في [XmlSchemaSet](../)؛ وإلا، **false**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [XmlSchemaSet](../)
* فئة [XmlSchema](../../xmlschema/)
* مساحة الاسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)