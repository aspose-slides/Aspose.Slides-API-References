---
title: IsDerivedFrom()
second_title: مرجع API Aspose.Slides للغة C++
description: تُعيد قيمة تُشير ما إذا كان نوع المخطط المشتق المحدد مشتقًا من نوع المخطط الأساسي المحدد.
type: docs
weight: 209
url: /ar/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) طريقة

تُعيد قيمة تُشير ما إذا كان نوع المخطط المشتق المحدد مشتقًا من نوع المخطط الأساسي المحدد.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | الكائن المشتق [XmlSchemaType](../) للاختبار. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | الـ[XmlSchemaType](../) الأساسي لاختبار المشتق [XmlSchemaType](../) ضده. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | إحدى قيم XmlSchemaDerivationMethod التي تمثل طريقة اشتقاق نوع لاستثناؤها من الاختبار. |

### قيمة الإرجاع

**true** إذا كان النوع المشتق مشتقًا من النوع الأساسي؛ وإلا، **false**.

## انظر أيضًا

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)