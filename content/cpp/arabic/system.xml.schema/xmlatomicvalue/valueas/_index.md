---
title: ValueAs()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع قيمة العنصر أو السمة XML المُصدق عليها كنوع محدد باستخدام كائن IXmlNamespaceResolver المحدد لحل بادئات النطاق.
type: docs
weight: 144
url: /ar/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) طريقة

Returns the validated XML element or attribute's value as the type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | النوع الذي يتم إرجاع قيمة العنصر أو السمة XML المُصادق عليها به. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | الكائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المستخدم لحل بادئات النطاق. |

### قيمة الإرجاع

قيمة العنصر أو السمة XML المُصادق عليها حسب النوع المطلوب.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XmlAtomicValue](../)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)