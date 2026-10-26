---
title: ReadToDescendant()
second_title: مرجع API Aspose.Slides برای C++
description: XmlReader را به عنصر فرزند بعدی با نام معتبر مشخص پیش می‌برد.
type: docs
weight: 911
url: /fa/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) متد

به [XmlReader](../) اجازه می‌دهد تا به عنصر فرزند بعدی با نام معتبر مشخص پیش برود.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام معتبر عنصری که می‌خواهید به آن حرکت کنید. |

### مقدار بازگشت

**true** اگر عنصری فرزند مطابق یافت شود؛ در غیر این صورت **false**. اگر عنصر فرزند مطابقت نداشته باشد، [XmlReader](../) در برچسب پایان (مقدار [XmlReader::get_NodeType](../get_nodetype/) برابر [XmlNodeType::EndElement](../../xmlnodetype/)) عنصر قرار می‌گیرد. اگر [XmlReader](../) هنگام فراخوانی [XmlReader::ReadToDescendant(String)](./) روی عنصری قرار نگرفته باشد، این متد **false** برمی‌گرداند و موقعیت [XmlReader](../) تغییر نمی‌کند.

## XmlReader::ReadToDescendant(String, String) متد

به [XmlReader](../) اجازه می‌دهد تا به عنصر فرزند بعدی با نام محلی و URI فضای نام مشخص پیش برود.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی عنصری که می‌خواهید به آن حرکت کنید. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصری که می‌خواهید به آن حرکت کنید. |

### مقدار بازگشت

**true** اگر عنصری فرزند مطابق یافت شود؛ در غیر این صورت **false**. اگر عنصر فرزند مطابقت نداشته باشد، [XmlReader](../) در برچسب پایان (مقدار [XmlReader::get_NodeType](../get_nodetype/) برابر [XmlNodeType::EndElement](../../xmlnodetype/)) عنصر قرار می‌گیرد. اگر [XmlReader](../) هنگام فراخوانی [XmlReader::ReadToDescendant(String,String)](./) روی عنصری قرار نگرفته باشد، این متد **false** برمی‌گرداند و موقعیت [XmlReader](../) تغییر نمی‌کند.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)