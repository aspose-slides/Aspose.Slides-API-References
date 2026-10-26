---
title: ChangeType()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل القيمة المحددة، والتي يكون نوعها أحد التمثيلات الصالحة لنوع مخطط XML الممثل بـ XmlSchemaDatatype، إلى نوع وقت التشغيل المحدد.
type: docs
weight: 66
url: /ar/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method

يقوم بتحويل القيمة المحددة، والتي يكون نوعها أحد التمثيلات الصالحة لنوع مخطط XML الممثل بـ [XmlSchemaDatatype](../)، إلى نوع وقت التشغيل المحدد.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | القيمة المدخلة للتحويل إلى النوع المحدد. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | نوع الهدف لتحويل القيمة المدخلة إليه. |

### قيمة الإرجاع

القيمة المدخلة المحوَّلة.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

يقوم بتحويل القيمة المحددة، والتي يكون نوعها أحد التمثيلات الصالحة لنوع مخطط XML الممثل بـ [XmlSchemaDatatype](../)، إلى نوع وقت التشغيل المحدد باستخدام [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) إذا كان [XmlSchemaDatatype](../) يمثل نوع **xs:QName** أو نوعًا مشتقًا منه.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | القيمة المدخلة للتحويل إلى النوع المحدد. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | نوع الهدف لتحويل القيمة المدخلة إليه. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) يُستخدم لحل اختصارات المساحات الاسمية. لا يُستَخدم إلا إذا كان [XmlSchemaDatatype](../) يمثل نوع **xs:QName** أو نوعًا مشتقًا منه. |

### قيمة الإرجاع

القيمة المدخلة المحوَّلة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlSchemaDatatype](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)