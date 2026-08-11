---
title: ValidateEndElement()
second_title: Aspose.Slides لـ C++ – مرجع API
description: يتحقق مما إذا كان محتوى النص للعنصر صالحًا وفقًا لنوع البيانات الخاص به للعناصر ذات المحتوى البسيط، ويتحقق مما إذا كان محتوى العنصر الحالي مكتملًا للعناصر ذات المحتوى المعقد.
type: docs
weight: 209
url: /ar/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) طريقة

يتحقق مما إذا كان محتوى النص للعنصر صالحًا وفقًا لنوع البيانات الخاص به للعناصر ذات المحتوى البسيط، ويتحقق مما إذا كان محتوى العنصر الحالي مكتملًا للعناصر ذات المحتوى المركب.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### المعاملات
| المعامل | النوع | الوصف |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | كائن [XmlSchemaInfo](../../xmlschemainfo/) يتم تعيين خصائصه عند نجاح التحقق من صحة العنصر. يمكن أن يكون هذا المعامل **nullptr**. |

### قيمة الإرجاع

قيمة النص التي تم تحليلها وتحديد نوعها للعنصر إذا كان للعنصر محتوى بسيط.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method

يتحقق مما إذا كان محتوى النص للعنصر المحدد صالحًا وفقًا لنوع بياناته.
```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | كائن [XmlSchemaInfo](../../xmlschemainfo/) يتم تعيين خصائصه عند نجاح التحقق من صحة محتوى النص للعنصر. يمكن أن يكون هذا المعامل **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | محتوى النص المكتوب للعنصر. |

### قيمة الإرجاع

المحتوى البسيط المكتوب للعنصر.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [XmlSchemaInfo](../../xmlschemainfo/)
* فئة [XmlSchemaValidator](../)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)