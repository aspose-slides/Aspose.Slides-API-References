---
title: MoveToAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: "زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، به ویژگی با مقدار XmlReader::get_Name مشخص شده حرکت می‌کند."
type: docs
weight: 625
url: /fa/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) متد

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، به ویژگی با مقدار [XmlReader::get_Name](../get_name/) مشخص حرکت می‌کند.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل ویژگی. |

### مقدار بازگشت

**true** اگر ویژگی پیدا شود؛ در غیر این صورت **false**. اگر **false** باشد، موقعیت خواننده تغییر نمی‌کند.

## XmlReader::MoveToAttribute(String, String) متد

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، به ویژگی با مقادیر [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) مشخص حرکت می‌کند.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام محلی ویژگی. |
| ns | [String](../../../system/string/) | URI فضای‌نام ویژگی. |

### مقدار بازگشت

**true** اگر ویژگی پیدا شود؛ در غیر این صورت **false**. اگر **false** باشد، موقعیت خواننده تغییر نمی‌کند.

## XmlReader::MoveToAttribute(int32_t) متد

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، به ویژگی با ایندکس مشخص حرکت می‌کند.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | ایندکس ویژگی. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)