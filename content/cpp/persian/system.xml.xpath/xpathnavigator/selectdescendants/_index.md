---
title: SelectDescendants()
second_title: مرجع API Aspose.Slides برای C++
description: تمام گره‌های فرعی گرهٔ فعلی را که دارای XPathNodeType مطابقت‌دار هستند، انتخاب می‌کند.
type: docs
weight: 859
url: /fa/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) متد

تمام گره‌های فرعی گرهٔ فعلی را که دارای XPathNodeType مطابقت‌دار هستند، انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType گره‌های فرعی. |
| matchSelf | **bool** | **true** برای شامل‌کردن گرهٔ زمینه در انتخاب؛ در غیر این صورت، **false**. |

### Return Value

یک [XPathNodeIterator](../../xpathnodeiterator/) که شامل گره‌های انتخاب‌شده است.

## XPathNavigator::SelectDescendants(String, String, bool) متد

تمام گره‌های فرعی گرهٔ فعلی را که دارای نام محلی و URI فضای نام مشخص‌شده هستند، انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی گره‌های فرعی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام گره‌های فرعی. |
| matchSelf | **bool** | **true** برای شامل‌کردن گرهٔ زمینه در انتخاب؛ در غیر این صورت، **false**. |

### Return Value

یک [XPathNodeIterator](../../xpathnodeiterator/) که شامل گره‌های انتخاب‌شده است.

## نگاه کنید به

* enum [XPathNodeType](../../xpathnodetype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathNodeIterator](../../xpathnodeiterator/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)