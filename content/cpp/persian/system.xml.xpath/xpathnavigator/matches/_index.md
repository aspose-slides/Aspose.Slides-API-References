---
title: Matches()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند که آیا گره فعلی با XPathExpression مشخص شده مطابقت دارد.
type: docs
weight: 820
url: /fa/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) متد


تعیین می‌کند که آیا گره فعلی با [XPathExpression](../../xpathexpression/) مشخص شده مطابقت دارد یا نه.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | یک شیء [XPathExpression](../../xpathexpression/) که شامل عبارت [XPath](../../) کامپایل‌شده است. |

### مقدار بازگشت

**true** اگر گره فعلی با [XPathExpression](../../xpathexpression/) مطابقت داشته باشد؛ در غیر این صورت **false**.

## XPathNavigator::Matches(String) متد


تعیین می‌کند که آیا گره فعلی با عبارت [XPath](../../) مشخص شده مطابقت دارد یا نه.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | عبارت [XPath](../../). |

### مقدار بازگشت

**true** اگر گره فعلی با عبارت [XPath](../../) مشخص شده مطابقت داشته باشد؛ در غیر این صورت **false**.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathExpression](../../xpathexpression/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)