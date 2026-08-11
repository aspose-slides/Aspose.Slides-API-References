---
title: MoveToNext()
second_title: Aspose.Slides برای C++ مرجع API
description: هنگامی که در یک کلاس مشتق بازنویسی شود، XPathNavigator را به گره خواهر بعدی گره جاری منتقل می‌کند.
type: docs
weight: 586
url: /fa/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() متد

When overridden in a derived class, moves the [XPathNavigator](../) to the next sibling node of the current node.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### مقدار بازگشتی

**true** اگر [XPathNavigator](../) با موفقیت به گره برادر بعدی منتقل شود؛ در غیر این صورت **false** اگر دیگر برادرهایی وجود نداشته باشد یا اگر [XPathNavigator](../) در حال حاضر روی یک گره ویژگی قرار داشته باشد. اگر **false** باشد، موقعیت [XPathNavigator](../) تغییر نمی‌کند.

## XPathNavigator::MoveToNext(String, String) متد

Moves the [XPathNavigator](../) to the next sibling node with the local name and namespace URI specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی گره برادر بعدی که باید به آن منتقل شود. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام گره برادر بعدی که باید به آن منتقل شود. |

### مقدار بازگشتی

**true** اگر [XPathNavigator](../) با موفقیت به گره برادر بعدی منتقل شود؛ **false** اگر دیگر برادرهایی وجود نداشته باشد یا اگر [XPathNavigator](../) در حال حاضر روی یک گره ویژگی قرار داشته باشد. اگر **false** باشد، موقعیت [XPathNavigator](../) تغییر نمی‌کند.

## XPathNavigator::MoveToNext(XPathNodeType) متد

Moves the [XPathNavigator](../) to the next sibling node of the current node that matches the XPathNodeType specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType گره برادر که باید به آن منتقل شود. |

### مقدار بازگشتی

**true** اگر [XPathNavigator](../) با موفقیت به گره برادر بعدی منتقل شود؛ در غیر این صورت **false** اگر دیگر برادرهایی وجود نداشته باشد یا اگر [XPathNavigator](../) در حال حاضر روی یک گره ویژگی قرار داشته باشد. اگر **false** باشد، موقعیت [XPathNavigator](../) تغییر نمی‌کند.

## موارد مرتبط

* شمارشی [XPathNodeType](../../xpathnodetype/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)