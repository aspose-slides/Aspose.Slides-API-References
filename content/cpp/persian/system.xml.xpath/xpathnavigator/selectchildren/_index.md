---
title: SelectChildren()
second_title: مرجع API Aspose.Slides برای C++
description: تمام گره‌های فرزند گرهٔ جاری که XPathNodeType مطابقت دارند را انتخاب می‌کند.
type: docs
weight: 833
url: /fa/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) متد

همهٔ گره‌های فرزند گرهٔ جاری که نوع XPathNodeType مطابق دارند را انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType گره‌های فرزند. |

### مقدار بازگشت

یک [XPathNodeIterator](../../xpathnodeiterator/) که شامل گره‌های انتخاب شده است.

## XPathNavigator::SelectChildren(String, String) متد

همهٔ گره‌های فرزند گرهٔ جاری که نام محلی و URI فضای نام مشخص شده را دارند را انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی گره‌های فرزند. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام گره‌های فرزند. |

### مقدار بازگشت

یک [XPathNodeIterator](../../xpathnodeiterator/) که شامل گره‌های انتخاب شده است.

## موارد مرتبط

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathNodeIterator](../../xpathnodeiterator/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)