---
title: MoveToAttribute()
second_title: Aspose.Slides برای مرجع API C++
description: به ویژگی با نام مشخص شده می‌رود.
type: docs
weight: 300
url: /fa/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) متد

به ویژگی با نام مشخص شده می‌رود.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل ویژگی. |

### مقدار برگشتی

**true** اگر ویژگی یافت شود؛ در غیر این صورت **false**. اگر **false** باشد، موقعیت خواننده تغییر نمی‌کند.

## XmlNodeReader::MoveToAttribute(String, String) متد

به ویژگی با نام محلی و URI فضای نام مشخص شده می‌رود.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | آدرس URI فضای‌نام ویژگی. |

### مقدار برگشتی

**true** اگر ویژگی یافت شود؛ در غیر این صورت **false**. اگر **false** باشد، موقعیت خواننده تغییر نمی‌کند.

## XmlNodeReader::MoveToAttribute(int32_t) متد

به ویژگی با اندیس مشخص شده می‌رود.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| attributeIndex | **int32_t** | اندیس ویژگی. |

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlNodeReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)