---
title: ValueAs()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: يرجع قيمة العقدة الحالية كـ Type المحدد، باستخدام كائن IXmlNamespaceResolver المحدد لحل بادئات النطاق.
type: docs
weight: 378
url: /ar/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) طريقة

يرجع قيمة العقدة الحالية كنوع محدد، باستخدام كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات النطاق.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | النوع لإرجاع قيمة العقدة الحالية كـ. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | كائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المستخدم لحل بادئات النطاق. |

### قيمة الإرجاع

قيمة العقدة الحالية كنوع مطلوب.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XPathNavigator](../)
* نطاق [System::Xml::XPath](../../)
* مكتبة [Aspose.Slides](../../../)