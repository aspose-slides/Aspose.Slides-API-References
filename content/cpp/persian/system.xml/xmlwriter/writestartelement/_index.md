---
title: WriteStartElement()
second_title: Aspose.Slides برای C++ مرجع API
description: هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، برچسب شروع مشخص‌شده را می‌نویسد و آن را با فضای نام داده‌شده مرتبط می‌سازد.
type: docs
weight: 92
url: /fa/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) متد

هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، برچسب شروع مشخص‌شده را می‌نویسد و آن را با فضای نام داده‌شده مرتبط می‌سازد.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی عنصر. |
| ns | const [String](../../../system/string/)\& | URI فضای نام برای ارتباط با عنصر. اگر این فضای نام قبلاً در محدوده باشد و پیشوندی مرتبط داشته باشد، نویسنده به‌طور خودکار همان پیشوند را نیز می‌نویسد. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) متد

هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، برچسب شروع مشخص‌شده را می‌نویسد و آن را با فضای نام و پیشوند داده‌شده مرتبط می‌سازد.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | پیشوند فضای نام عنصر. |
| localName | const [String](../../../system/string/)\& | نام محلی عنصر. |
| ns | const [String](../../../system/string/)\& | URI فضای نام برای ارتباط با عنصر. |

## XmlWriter::WriteStartElement(const String\&) متد

هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، برچسب شروعی با نام محلی مشخص‌شده می‌نویسد.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | نام محلی عنصر. |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlWriter](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)