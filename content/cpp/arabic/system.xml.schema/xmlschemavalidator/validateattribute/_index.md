---
title: ValidateAttribute()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بالتحقق من اسم الخاصية، معرف URI للنطاق، والقيمة في سياق العنصر الحالي.
type: docs
weight: 144
url: /ar/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) طريقة

يقوم بالتحقق من اسم الخاصية، معرف URI للنطاق، والقيمة في سياق العنصر الحالي.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للخاصية المراد التحقق منها. |
| namespaceUri | const [String](../../../system/string/)\& | معرف URI للنطاق للخاصية المراد التحقق منها. |
| attributeValue | const [String](../../../system/string/)\& | قيمة الخاصية المراد التحقق منها. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | كائن [XmlSchemaInfo](../../xmlschemainfo/) يتم تعيين خصائصه عند التحقق الناجح من الخاصية. يمكن أن يكون هذا المعامل **nullptr**. |

### قيمة الإرجاع

قيمة الخاصية التي تم التحقق منها.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) طريقة

يقوم بالتحقق من اسم الخاصية، معرف URI للنطاق، والقيمة في سياق العنصر الحالي.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | الاسم المحلي للخاصية المراد التحقق منها. |
| namespaceUri | const [String](../../../system/string/)\& | معرف URI للنطاق للخاصية المراد التحقق منها. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | دالة رد نداء XmlValueGetter تُستخدم لتمرير قيمة الخاصية كنوع متوافق مع نوع XML [Schema](../../) Definition Language (XSD) للخاصية. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | كائن [XmlSchemaInfo](../../xmlschemainfo/) يتم تعيين خصائصه عند التحقق الناجح من الخاصية. هذا المعامل ويمكن أن يكون **nullptr**. |

### قيمة الإرجاع

قيمة الخاصية التي تم التحقق منها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)