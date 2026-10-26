---
title: Remove()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل مخطط تعريف لغة XML Schema (XSD) المحدد من XmlSchemaSet.
type: docs
weight: 170
url: /ar/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) طريقة

يزيل مخطط تعريف اللغة (XSD) XML [Schema](../../) المحدد من [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | الكائن [XmlSchema](../../xmlschema/) لإزالته من [XmlSchemaSet](../). |

### قيمة الإرجاع

الكائن [XmlSchema](../../xmlschema/) الذي أُزيل من [XmlSchemaSet](../) أو **nullptr** إذا لم يتم العثور على الـ schema في [XmlSchemaSet](../).

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)