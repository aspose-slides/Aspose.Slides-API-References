---
title: MoveToChild()
second_title: مرجع API Aspose.Slides برای C++
description: XPathNavigator را به گره فرزند با نام محلی و URI فضای نام مشخص شده منتقل می‌کند.
type: docs
weight: 690
url: /fa/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) متد

[XPathNavigator](../) را به گره فرزند با نام محلی و URI فضای نام مشخص‌شده منتقل می‌کند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی گره فرزند برای انتقال. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام گره فرزند برای انتقال. |

### مقدار بازگشت

**true** اگر [XPathNavigator](../) با موفقیت به گره فرزند منتقل شود؛ در غیر این صورت، **false**. اگر **false** باشد، موقعیت [XPathNavigator](../) بدون تغییر می‌ماند.

## XPathNavigator::MoveToChild(XPathNodeType) متد

[XPathNavigator](../) را به گره فرزند از نوع XPathNodeType مشخص‌شده منتقل می‌کند.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType گره فرزند برای انتقال. |

### مقدار بازگشت

**true** اگر [XPathNavigator](../) با موفقیت به گره فرزند منتقل شود؛ در غیر این صورت، **false**. اگر **false** باشد، موقعیت [XPathNavigator](../) بدون تغییر می‌ماند.

## موارد مرتبط

* شمارش [XPathNodeType](../../xpathnodetype/)
* کلاس [String](../../../system/string/)
* کلاس [XPathNavigator](../)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)