---
title: AppendChild()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء XmlWriter را برمی‌گرداند که برای ایجاد یک یا چند گره فرزند جدید در انتهای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود.
type: docs
weight: 885
url: /fa/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() متد

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) را برمی‌گرداند که برای ایجاد یک یا چند گره فرزند جدید در انتهای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### مقدار بازگشتی

یک شیء [XmlWriter](../../../system.xml/xmlwriter/) که برای ایجاد گره‌های فرزند جدید در انتهای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود.

## XPathNavigator::AppendChild(String) متد

یک گره فرزند جدید را در انتهای فهرست گره‌های فرزند گرهٔ جاری با استفاده از رشتهٔ دادهٔ XML مشخص‌شده ایجاد می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | رشتهٔ دادهٔ XML برای گره فرزند جدید. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) متد

یک گره فرزند جدید را در انتهای فهرست گره‌های فرزند گرهٔ جاری با استفاده از محتوای XML شیء [XmlReader](../../../system.xml/xmlreader/) مشخص‌شده ایجاد می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | شیء [XmlReader](../../../system.xml/xmlreader/) که بر دادهٔ XML برای گره فرزند جدید موقعیت دارد. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) متد

یک گره فرزند جدید را در انتهای فهرست گره‌های فرزند گرهٔ جاری با استفاده از گره‌های موجود در [XPathNavigator](../) مشخص‌شده ایجاد می‌کند.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | شیء [XPathNavigator](../) که بر گره‌ای که به عنوان گره فرزند جدید اضافه می‌شود موقعیت دارد. |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlWriter](../../../system.xml/xmlwriter/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)