---
title: ValueAs()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع قيمة العنصر بالنوع المحدد.
type: docs
weight: 131
url: /ar/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) طريقة

يرجع قيمة العنصر بالنوع المحدد.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | النوع الذي يُرجع به قيمة العنصر. |

### قيمة الإرجاع

قيمة العنصر بالنوع المطلوب.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) طريقة

عند تجاوزه في فئة مشتقة، يرجع قيمة العنصر بالنوع المحدد باستخدام كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات النطاق.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | النوع الذي يُرجع به قيمة العنصر. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المستخدم لحل بادئات النطاق. |

### قيمة الإرجاع

قيمة العنصر بالنوع المطلوب.

## انظر أيضًا

* نوع تعريف [SharedPtr](../../../system/sharedptr/)
* الفئة [Object](../../../system/object/)
* الفئة [TypeInfo](../../../system/typeinfo/)
* الفئة [XPathItem](../)
* الفئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* النطاق [System::Xml::XPath](../../)
* المكتبة [Aspose.Slides](../../../)