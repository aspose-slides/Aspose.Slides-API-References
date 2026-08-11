---
title: SelectAncestors()
second_title: مرجع API Aspose.Slides برای C++
description: تمام گره‌های اسلاف گرهٔ فعلی که دارای XPathNodeType مطابق هستند را انتخاب می‌کند.
type: docs
weight: 846
url: /fa/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) متد

تمام گره‌های اسلاف گرهٔ فعلی را که دارای XPathNodeType مطابق هستند انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType گره‌های اسلاف. |
| matchSelf | **bool** | برای شامل کردن گرهٔ زمینه در انتخاب، **true**؛ در غیر این صورت، **false**. |

### مقدار بازگشت

یک [XPathNodeIterator](../../xpathnodeiterator/) که گره‌های انتخاب‌شده را شامل می‌شود. گره‌های بازگردانده‌شده به ترتیب معکوس سند هستند.

## XPathNavigator::SelectAncestors(String, String, bool) متد

تمام گره‌های اسلاف گرهٔ فعلی را که نام محلی و URI فضای‌نام مشخص شده را دارند انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی گره‌های اسلاف. |
| namespaceURI | [String](../../../system/string/) | URI فضای‌نام گره‌های اسلاف. |
| matchSelf | **bool** | برای شامل کردن گرهٔ زمینه در انتخاب، **true**؛ در غیر این صورت، **false**. |

### مقدار بازگشت

یک [XPathNodeIterator](../../xpathnodeiterator/) که گره‌های انتخاب‌شده را شامل می‌شود. گره‌های بازگردانده‌شده به ترتیب معکوس سند هستند.

## موارد مرتبط

* enum [XPathNodeType](../../xpathnodetype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathNodeIterator](../../xpathnodeiterator/)
* کلاس [XPathNavigator](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)