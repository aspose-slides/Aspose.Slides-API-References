---
title: PrependChild()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء XmlWriter را برمی‌گرداند که برای ایجاد یک گرهٔ فرزند جدید در ابتدای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود.
type: docs
weight: 872
url: /fa/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() متد

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) را برمی‌گرداند که برای ایجاد یک گره فرزند جدید در ابتدای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### مقدار بازگشت

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) که برای ایجاد یک گره فرزند جدید در ابتدای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود.

## XPathNavigator::PrependChild(String) متد

یک گره فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری ایجاد می‌کند با استفاده از رشتهٔ XML مشخص‌شده.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | رشتهٔ دادهٔ XML برای گره فرزند جدید. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) متد

یک گره فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری ایجاد می‌کند با استفاده از محتوای XML شیء [XmlReader](../../../system.xml/xmlreader/) مشخص‌شده.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | یک شیء [XmlReader](../../../system.xml/xmlreader/) که روی دادهٔ XML برای گره فرزند جدید قرار دارد. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) متد

یک گره فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری ایجاد می‌کند با استفاده از گره‌های موجود در شیء [XPathNavigator](../) مشخص‌شده.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | یک شیء [XPathNavigator](../) که روی گره‌ای که به‌عنوان گره فرزند جدید اضافه می‌شود، قرار دارد. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlWriter](../../../system.xml/xmlwriter/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* فضای‌نام [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)