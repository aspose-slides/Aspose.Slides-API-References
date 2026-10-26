---
title: XmlTextWriter()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از کلاس XmlTextWriter را با استفاده از جریان و رمزگذاری مشخص شده ایجاد می‌کند.
type: docs
weight: 183
url: /fa/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) سازنده

یک نمونه از کلاس [XmlTextWriter](../) را با استفاده از جریان و رمزگذاری مشخص شده ایجاد می‌کند.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که می‌خواهید به آن بنویسید. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری برای تولید. اگر رمزگذاری **nullptr** باشد، جریان را به صورت UTF-8 می‌نویسد و ویژگی encoding را از **ProcessingInstruction** حذف می‌کند. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) سازنده

یک نمونه از کلاس [XmlTextWriter](../) را با استفاده از فایل مشخص شده ایجاد می‌کند.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایل برای نوشتن. اگر فایل موجود باشد، آن را برش می‌دهد و محتوای جدید را روی آن می‌نویسد. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری برای تولید. اگر رمزگذاری **nullptr** باشد، فایل را به صورت UTF-8 می‌نویسد و ویژگی encoding را از **ProcessingInstruction** حذف می‌کند. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) سازنده

یک نمونه از کلاس [XmlTextWriter](../) را با استفاده از TextWriter مشخص شده ایجاد می‌کند.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriterی که باید به آن نوشت. فرض می‌شود که TextWriter قبلاً به رمزگذاری صحیح تنظیم شده است. |

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlTextWriter](../)
* Class [String](../../../system/string/)
* Class [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)