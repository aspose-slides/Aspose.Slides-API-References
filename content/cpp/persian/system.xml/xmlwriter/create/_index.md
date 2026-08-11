---
title: Create()
second_title: Aspose.Slides برای C++ – مرجع API
description: یک نمونه جدید XmlWriter را با استفاده از نام فایل مشخص شده ایجاد می‌کند.
type: docs
weight: 469
url: /fa/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از نام فایل مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | فایلی که می‌خواهید در آن بنویسید. [XmlWriter](../) یک فایل در مسیر مشخص شده ایجاد می‌کند و به آن به‌صورت XML 1.0 نوشتار متنی می‌نویسد. **outputFileName** باید یک مسیر فایل‌سیستم باشد. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از نام فایل و شیء [XmlWriterSettings](../../xmlwritersettings/) ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | فایلی که می‌خواهید در آن بنویسید. [XmlWriter](../) یک فایل در مسیر مشخص شده ایجاد می‌کند و به آن به‌صورت XML 1.0 نوشتار متنی می‌نویسد. **outputFileName** باید یک مسیر فایل‌سیستم باشد. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | شیء [XmlWriterSettings](../../xmlwritersettings/) مورد استفاده برای پیکربندی نمونه جدید [XmlWriter](../). اگر این مقدار **nullptr** باشد، یک [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات پیش‌فرض استفاده می‌شود. اگر [XmlWriter](../) همراه با متد XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) استفاده شود، باید از مقدار XslCompiledTransform::get_OutputSettings برای دریافت شیء [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات صحیح استفاده کنید. این کار اطمینان می‌دهد که شیء ایجاد شده [XmlWriter](../) تنظیمات خروجی صحیح را داشته باشد. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از جریان مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان‌ایی که می‌خواهید در آن بنویسید. [XmlWriter](../) نوشتار متنی XML 1.0 را می‌نویسد و به جریان مشخص شده اضافه می‌کند. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از جریان و شیء [XmlWriterSettings](../../xmlwritersettings/) ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان‌ایی که می‌خواهید در آن بنویسید. [XmlWriter](../) نوشتار متنی XML 1.0 را می‌نویسد و به جریان مشخص شده اضافه می‌کند. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | شیء [XmlWriterSettings](../../xmlwritersettings/) مورد استفاده برای پیکربندی نمونه جدید [XmlWriter](../). اگر این مقدار **nullptr** باشد، یک [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات پیش‌فرض استفاده می‌شود. اگر [XmlWriter](../) همراه با متد XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) استفاده شود، باید از مقدار XslCompiledTransform::get_OutputSettings برای دریافت شیء [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات صحیح استفاده کنید. این کار اطمینان می‌دهد که شیء ایجاد شده [XmlWriter](../) تنظیمات خروجی صحیح را داشته باشد. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از TextWriter مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter‌ای که می‌خواهید در آن بنویسید. [XmlWriter](../) نوشتار متنی XML 1.0 را می‌نویسد و به TextWriter مشخص شده اضافه می‌کند. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از TextWriter و شیء [XmlWriterSettings](../../xmlwritersettings/) ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter‌ای که می‌خواهید در آن بنویسید. [XmlWriter](../) نوشتار متنی XML 1.0 را می‌نویسد و به TextWriter مشخص شده اضافه می‌کند. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | شیء [XmlWriterSettings](../../xmlwritersettings/) مورد استفاده برای پیکربندی نمونه جدید [XmlWriter](../). اگر این مقدار **nullptr** باشد، یک [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات پیش‌فرض استفاده می‌شود. اگر [XmlWriter](../) همراه با متد XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) استفاده شود، باید از مقدار XslCompiledTransform::get_OutputSettings برای دریافت شیء [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات صحیح استفاده کنید. این کار اطمینان می‌دهد که شیء ایجاد شده [XmlWriter](../) تنظیمات خروجی صحیح را داشته باشد. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از [Text::StringBuilder](../../../system.text/stringbuilder/) مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) که می‌خواهید به آن بنویسید. محتوای نوشته‌شده توسط [XmlWriter](../) به [Text::StringBuilder](../../../system.text/stringbuilder/) اضافه می‌شود. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از شیء [Text::StringBuilder](../../../system.text/stringbuilder/) و [XmlWriterSettings](../../xmlwritersettings/) ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) که می‌خواهید به آن بنویسید. محتوای نوشته‌شده توسط [XmlWriter](../) به [Text::StringBuilder](../../../system.text/stringbuilder/) اضافه می‌شود. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | شیء [XmlWriterSettings](../../xmlwritersettings/) مورد استفاده برای پیکربندی نمونه جدید [XmlWriter](../). اگر این مقدار **nullptr** باشد، یک [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات پیش‌فرض استفاده می‌شود. اگر [XmlWriter](../) همراه با متد XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) استفاده شود، باید از مقدار XslCompiledTransform::get_OutputSettings برای دریافت شیء [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات صحیح استفاده کنید. این کار اطمینان می‌دهد که شیء ایجاد شده [XmlWriter](../) تنظیمات خروجی صحیح را داشته باشد. |

### مقدار بازگشت

یک شیء [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از شیء [XmlWriter](../) مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | شیء [XmlWriter](../) که می‌خواهید به عنوان نوشتار زیرین استفاده کنید. |

### مقدار بازگشت

یک شیء [XmlWriter](../) که دور شیء [XmlWriter](../) مشخص شده پیچیده شده است.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) متد

یک نمونه جدید [XmlWriter](../) را با استفاده از شیء [XmlWriter](../) و [XmlWriterSettings](../../xmlwritersettings/) مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | شیء [XmlWriter](../) که می‌خواهید به عنوان نوشتار زیرین استفاده کنید. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | شیء [XmlWriterSettings](../../xmlwritersettings/) مورد استفاده برای پیکربندی نمونه جدید [XmlWriter](../). اگر این مقدار **nullptr** باشد، یک [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات پیش‌فرض استفاده می‌شود. اگر [XmlWriter](../) همراه با متد XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) استفاده شود، باید از مقدار XslCompiledTransform::get_OutputSettings برای دریافت شیء [XmlWriterSettings](../../xmlwritersettings/) با تنظیمات صحیح استفاده کنید. این کار اطمینان می‌دهد که شیء ایجاد شده [XmlWriter](../) تنظیمات خروجی صحیح را داشته باشد. |

### مقدار بازگشت

یک شیء [XmlWriter](../) که دور شیء [XmlWriter](../) مشخص شده پیچیده شده است.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)