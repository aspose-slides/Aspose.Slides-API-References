---
title: ReadContentAs()
second_title: Aspose.Slides للغة C++ دليل مرجع API
description: يقرأ المحتوى ككائن من النوع المحدد.
type: docs
weight: 456
url: /ar/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) طريقة

يقرأ المحتوى ككائن من النوع المحدد.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوع القيمة التي سيتم إرجاعها. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | كائن [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) يُستخدم لحل أي بادئات مساحة اسم مرتبطة بتحويل النوع. على سبيل المثال، يمكن استخدامه عند تحويل كائن [XmlQualifiedName](../../xmlqualifiedname/) إلى **xs:string**. يمكن أن تكون هذه القيمة **nullptr**. |

### قيمة الإرجاع

المحتوى النصي المتسلق أو قيمة السمة المحوّلة إلى النوع المطلوب.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* فئة [XmlReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)