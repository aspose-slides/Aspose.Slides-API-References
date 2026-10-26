---
title: Reprocess()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد معالجة مخطط تعريف لغة XML Schema (XSD) الموجود بالفعل في XmlSchemaSet.
type: docs
weight: 222
url: /ar/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) طريقة

يعيد معالجة مخطط تعريف لغة XML [Schema](../../) (XSD) الموجود بالفعل في [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | المخطط لإعادة معالجته. |

### قيمة الإرجاع

كائن [XmlSchema](../../xmlschema/) إذا كان المخطط مخططًا صالحًا. إذا لم يكن المخطط صالحًا وتم تحديد ValidationEventHandler، يتم إرجاع **nullptr** ويتم إثارة حدث التحقق المناسب. خلاف ذلك، يتم إلقاء استثناء XmlSchemaException.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchema](../../xmlschema/)
* فئة [XmlSchemaSet](../)
* مساحة اسم [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)