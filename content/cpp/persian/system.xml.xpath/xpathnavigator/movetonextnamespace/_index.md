---
title: MoveToNextNamespace()
second_title: Aspose.Slides برای مرجع API C++
description: زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، XPathNavigator را به گره فضای‌نامی بعدی که با XPathNamespaceScope مشخص شده مطابقت دارد، منتقل می‌کند.
type: docs
weight: 573
url: /fa/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) متد

زمانی که در کلاس مشتق‌شده بازنویسی می‌شود، [XPathNavigator](../) را به گره فضای‌نامی بعدی که مطابق با XPathNamespaceScope مشخص شده، انتقال می‌دهد.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | یک مقدار XPathNamespaceScope که محدوده فضای‌نامی را توصیف می‌کند. |

### مقدار بازگشت

**true** اگر [XPathNavigator](../) با موفقیت به گره فضای‌نامی بعدی منتقل شود؛ در غیر این صورت، **false**. اگر **false** باشد، موقعیت [XPathNavigator](../) بدون تغییر باقی می‌ماند.

## XPathNavigator::MoveToNextNamespace() متد

[XPathNavigator](../) را به گره فضای‌نامی بعدی منتقل می‌کند.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### مقدار بازگشت

**true** اگر [XPathNavigator](../) با موفقیت به گره فضای‌نامی بعدی منتقل شود؛ در غیر این صورت، **false**. اگر **false** باشد، موقعیت [XPathNavigator](../) بدون تغییر باقی می‌ماند.

## موارد مرتبط

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* کلاس [XPathNavigator](../)
* فضای‌نامی [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)