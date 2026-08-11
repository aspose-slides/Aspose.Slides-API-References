---
title: get_Current()
second_title: مرجع برنامه‌نویسی Aspose.Slides برای C++
description: زمانی که در یک کلاس‌مشتق بازنویسی می‌شود، شیء XPathNavigator را برای این XPathNodeIterator دریافت می‌کند که بر روی گرهٔ زمینهٔ فعلی موقعیت دارد.
type: docs
weight: 1
url: /fa/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() متد

When overridden in a derived class, gets the [XPathNavigator](../../xpathnavigator/) object for this [XPathNodeIterator](../), positioned on the current context node.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### مقدار بازگشتی

یک شیء [XPathNavigator](../../xpathnavigator/) که بر روی گرهٔ زمینه‌ای که مجموعه گره‌ها از آن انتخاب شده است، موقعیت‌دار است. [XPathNodeIterator::MoveNext](../movenext/) متد باید فراخوانی شود تا [XPathNodeIterator](../) به اولین گره در مجموعهٔ انتخاب شده منتقل شود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathNavigator](../../xpathnavigator/)
* کلاس [XPathNodeIterator](../)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)