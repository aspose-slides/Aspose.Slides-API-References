---
title: MoveToAttribute()
second_title: مرجع API Aspose.Slides برای C++
description: به ویژگی‌ای که نام مشخص‌شده دارد می‌رود.
type: docs
weight: 508
url: /fa/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) متد

به ویژگی‌ای که نام مشخص‌شده دارد می‌رود.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل ویژگی. |

### مقدار بازگشت

**true** اگر ویژگی پیدا شود؛ در غیر این صورت **false**. اگر **false**، موقعیت خواننده تغییر نمی‌کند.

## XmlTextReader::MoveToAttribute(String, String) متد

به ویژگی‌ای که نام محلی و URI فضای نام مشخص‌شده دارد می‌رود.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی ویژگی. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام ویژگی. |

### مقدار بازگشت

**true** اگر ویژگی پیدا شود؛ در غیر این صورت **false**. اگر **false**، موقعیت خواننده تغییر نمی‌کند.

## XmlTextReader::MoveToAttribute(int32_t) متد

به ویژگی‌ای که شاخص مشخص‌شده را دارد می‌رود.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **int32_t** | شاخص ویژگی. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlTextReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)