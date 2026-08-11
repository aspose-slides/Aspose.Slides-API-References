---
title: InsertAfter()
second_title: مرجع API Aspose.Slides for C++
description: یک شیء XmlWriter را برمی‌گرداند که برای ایجاد یک گره هم‌سطح جدید پس از گره فعلی انتخاب‌شده استفاده می‌شود.
type: docs
weight: 898
url: /fa/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() متد

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) را برمی‌گرداند که برای ایجاد یک گره برادر جدید پس از گره فعلی انتخاب‌شده استفاده می‌شود.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### مقدار بازگشتی

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) را برمی‌گرداند که برای ایجاد یک گره برادر جدید پس از گره فعلی انتخاب‌شده استفاده می‌شود.

## XPathNavigator::InsertAfter(String) متد

یک گره برادر جدید پس از گره فعلی انتخاب‌شده با استفاده از رشته XML مشخص‌شده ایجاد می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | رشته داده XML برای گره برادر جدید. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) متد

یک گره برادر جدید پس از گره فعلی انتخاب‌شده با استفاده از محتویات XML شیء [XmlReader](../../../system.xml/xmlreader/) مشخص‌شده ایجاد می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | یک شیء [XmlReader](../../../system.xml/xmlreader/) که بر روی داده XML برای گره برادر جدید موقعیت یافته است. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) متد

یک گره برادر جدید پس از گره فعلی انتخاب‌شده با استفاده از گره‌های موجود در شیء [XPathNavigator](../) مشخص‌شده ایجاد می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | یک شیء [XPathNavigator](../) که بر روی گره‌ای که به عنوان گره برادر جدید اضافه می‌شود موقعیت یافته است. |

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlWriter](../../../system.xml/xmlwriter/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* فضای نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)