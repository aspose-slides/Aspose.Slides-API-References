---
title: ReadToFollowing()
second_title: مرجع API Aspose.Slides برای C++
description: تا زمانی که عنصری با نام کامل مشخص‌شده یافت شود، می‌خواند.
type: docs
weight: 898
url: /fa/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) متد

تا زمانی که عنصری با نام کامل مشخص‌شده پیدا شود، می‌خواند.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل عنصر. |

### مقدار بازگشت

**true** اگر عنصری مطابقت‌کننده پیدا شود؛ در غیر این صورت **false** و [XmlReader](../) در وضعیت پایان فایل است.

## XmlReader::ReadToFollowing(String, String) متد

تا زمانی که عنصری با نام محلی و URI فضای نام مشخص‌شده پیدا شود، می‌خواند.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی عنصر. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصر. |

### مقدار بازگشت

**true** اگر عنصری مطابقت‌کننده پیدا شود؛ در غیر این صورت **false** و [XmlReader](../) در وضعیت پایان فایل است.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)