---
title: SetContext()
second_title: Aspose.Slides برای C++ مرجع API
description: زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، شیء XmlNamespaceManager را برای حل فضای نام مشخص می‌کند.
type: docs
weight: 53
url: /fa/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) متد

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، شیء [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) را برای حل فضای نام مشخص می‌کند.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | یک شیء [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) برای حل فضای نام استفاده می‌شود. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) متد

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) را برای حل فضای نام مشخص می‌کند.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | شیئی که رابط [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) را پیاده‌سازی می‌کند برای حل فضای نام استفاده می‌شود. |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* کلاس [XPathExpression](../)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)