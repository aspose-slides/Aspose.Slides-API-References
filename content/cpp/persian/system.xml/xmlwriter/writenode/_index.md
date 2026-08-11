---
title: WriteNode()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق بازنویسی می‌شود، همه چیز را از خواننده به نویسنده کپی می‌کند و خواننده را به ابتدای خواهر بعدی منتقل می‌سازد.
type: docs
weight: 430
url: /fa/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) متد

زمانی که در یک کلاس مشتق بازنویسی می‌شود، تمام موارد را از خواننده به نویسنده کپی می‌کند و خواننده را به ابتدای خواهر بعدی منتقل می‌سازد.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) برای خواندن. |
| defattr | **bool** | **true** برای کپی کردن ویژگی‌های پیش‌فرض از [XmlReader](../../xmlreader/)؛ در غیر این صورت، **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) متد

تمام موارد را از شیء XPathNavigator به نویسنده کپی می‌کند. موقعیت XPathNavigator بدون تغییر می‌ماند.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | XPathNavigator برای کپی کردن. |
| defattr | **bool** | **true** برای کپی کردن ویژگی‌های پیش‌فرض؛ در غیر این صورت، **false**. |

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlReader](../../xmlreader/)
* کلاس [XmlWriter](../)
* کلاس [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)