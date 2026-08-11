---
title: ReadElementContentAs()
second_title: مرجع API Aspose.Slides للغة C++
description: يقرأ محتوى العنصر كنوع مطلوب.
type: docs
weight: 586
url: /ar/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) طريقة

يقرأ محتوى العنصر كنوع مطلوب.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوع القيمة التي سيتم إرجاعها. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | كائن [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) يُستخدم لحل أي بادئات مساحة اسم تتعلق بتحويل النوع. |

### قيمة الإرجاع

محتوى العنصر محول إلى كائن من النوع المطلوب.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) طريقة

يتحقق من أن الاسم المحلي المحدد ومعرّف مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ محتوى العنصر كنوع مطلوب.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوع القيمة التي سيتم إرجاعها. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | كائن [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) يُستخدم لحل أي بادئات مساحة اسم تتعلق بتحويل النوع. |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر. |
| namespaceURI | [String](../../../system/string/) | معرّف مساحة الاسم للعنصر. |

### قيمة الإرجاع

محتوى العنصر محول إلى كائن من النوع المطلوب.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* فئة [XmlReader](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)