---
title: idx_get()
second_title: Aspose.Slides لـ C++ مرجع API
description: تُرجِع XmlSchema المرتبطة بمُعرّف مساحة الاسم المُعطى.
type: docs
weight: 53
url: /ar/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) method

تُرجِع [XmlSchema](../../xmlschema/) المرتبطة بمُعرّف مساحة الاسم المُعطى.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | مُعرّف مساحة الاسم المرتبط بالمخطط الذي تريد إرجاعه. عادةً ما يكون هذا هو **targetNamespace** للمخطط. |

### قيمة الإرجاع

ال[XmlSchema](../../xmlschema/) المرتبط بمُعرّف مساحة الاسم؛ **nullptr** إذا لم يكن هناك مخطط محمَّل مرتبط بمساحة الاسم المُعطاة أو إذا كانت مساحة الاسم مرتبطة بمخطط XDR.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchema](../../xmlschema/)
* فئة [String](../../../system/string/)
* فئة [XmlSchemaCollection](../)
* فضاء الأسماء [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)