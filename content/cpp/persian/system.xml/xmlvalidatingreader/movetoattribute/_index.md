---
title: MoveToAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: به ویژگی با نام مشخص شده می‌رود.
type: docs
weight: 456
url: /fa/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) متد

به ویژگی با نام مشخص شده می‌رود.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل ویژگی. |

### مقدار بازگشت

**true** اگر ویژگی یافت شود؛ در غیر این صورت **false**. اگر **false**، موقعیت خواننده تغییر نمی‌کند.

## XmlValidatingReader::MoveToAttribute(String, String) متد

به ویژگی با نام محلی و شناسهٔ یکنواخت منبع (URI) فضای نام مشخص شده می‌رود.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای‌نام ویژگی. |

### مقدار بازگشت

**true** اگر ویژگی یافت شود؛ در غیر این صورت **false**. اگر **false**، موقعیت خواننده تغییر نمی‌کند.

## XmlValidatingReader::MoveToAttribute(int32_t) متد

به ویژگی با اندیس مشخص شده می‌رود.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | اندیس ویژگی. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlValidatingReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)