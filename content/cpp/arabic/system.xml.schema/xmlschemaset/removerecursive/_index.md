---
title: RemoveRecursive()
second_title: مرجع API Aspose.Slides للـ C++
description: يزيل مخطط لغة تعريف XML Schema (XSD) المحدد وجميع المخططات التي يستوردها من XmlSchemaSet.
type: docs
weight: 183
url: /ar/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) method

يزيل مخطط XSD المحدد للغة تعريف XML [Schema](../../) وجميع المخططات التي يستوردها من [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | الكائن [XmlSchema](../../xmlschema/) لإزالته من [XmlSchemaSet](../). |

### قيمة الإرجاع

**true** إذا تم إزالة الكائن [XmlSchema](../../xmlschema/) وجميع استيراداته بنجاح؛ وإلا، **false**.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)