---
title: InsertBefore()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء XmlWriter را برمی‌گرداند که برای ایجاد یک گره خواهر جدید قبل از گره انتخاب‌شده فعلی استفاده می‌شود.
type: docs
weight: 911
url: /fa/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() متد


یک شیء [XmlWriter](../../../system.xml/xmlwriter/) را برمی‌گرداند که برای ایجاد یک گره خواهر جدید قبل از گره انتخاب‌شده فعلی استفاده می‌شود.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### مقدار بازگشت

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) را برمی‌گرداند که برای ایجاد یک گره خواهر جدید قبل از گره انتخاب‌شده فعلی استفاده می‌شود.

## XPathNavigator::InsertBefore(String) متد


یک گره خواهر جدید قبل از گره انتخاب‌شده فعلی ایجاد می‌کند که از رشته XML مشخص‌شده استفاده می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | رشته داده XML برای گره خواهر جدید. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) متد


یک گره خواهر جدید قبل از گره انتخاب‌شده فعلی ایجاد می‌کند که از محتوای XML شیء [XmlReader](../../../system.xml/xmlreader/) مشخص‌شده استفاده می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | شیء [XmlReader](../../../system.xml/xmlreader/) که بر روی داده XML برای گره خواهر جدید قرار دارد. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) متد


یک گره خواهر جدید قبل از گره انتخاب‌شده فعلی ایجاد می‌کند که از گره‌های موجود در [XPathNavigator](../) مشخص‌شده استفاده می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | شیء [XPathNavigator](../) که بر روی گره‌ای که به عنوان گره خواهر جدید اضافه می‌شود، قرار دارد. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlWriter](../../../system.xml/xmlwriter/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)