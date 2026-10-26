---
title: ValueAs()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار آیتم را به عنوان نوع مشخص‌شده برمی‌گرداند.
type: docs
weight: 131
url: /fa/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) متد


مقدار آیتم را به عنوان نوع مشخص‌شده برمی‌گرداند.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوعی که مقدار آیتم باید به آن بازگردانده شود. |

### مقدار بازگشتی

مقدار آیتم به عنوان نوع درخواست‌شده.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) متد


When overridden in a derived class, returns the item's value as the type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوعی که مقدار آیتم باید به آن بازگردانده شود. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) مورد استفاده برای حل پیشوندهای فضای نام. |

### مقدار بازگشتی

مقدار آیتم به عنوان نوع درخواست‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [XPathItem](../)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فضای‌نام [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)