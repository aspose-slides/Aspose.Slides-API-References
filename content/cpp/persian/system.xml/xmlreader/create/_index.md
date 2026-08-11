---
title: Create()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید XmlReader با URI مشخص ایجاد می‌کند.
type: docs
weight: 1015
url: /fa/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) متد

یک نمونه جدید [XmlReader](../) با URI مشخص ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI برای فایلی که شامل داده‌های XML است. کلاس [XmlUrlResolver](../../xmlurlresolver/) برای تبدیل مسیر به یک نمایه دادهٔ استاندارد استفاده می‌شود. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از URI و تنظیمات مشخص ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI برای فایلی که شامل داده‌های XML است. شیء [XmlResolver](../../xmlresolver/) روی شیء [XmlReaderSettings](../../xmlreadersettings/) برای تبدیل مسیر به یک نمایه دادهٔ استاندارد استفاده می‌شود. اگر مقدار XmlReaderSettings::get_XmlResolver **nullptr** باشد، یک شیء جدید [XmlUrlResolver](../../xmlurlresolver/) استفاده می‌شود. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از URI، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI برای فایلی که شامل داده‌های XML است. شیء [XmlResolver](../../xmlresolver/) روی شیء [XmlReaderSettings](../../xmlreadersettings/) برای تبدیل مسیر به یک نمایه دادهٔ استاندارد استفاده می‌شود. اگر مقدار XmlReaderSettings::get_XmlResolver **nullptr** باشد، یک شیء جدید [XmlUrlResolver](../../xmlurlresolver/) استفاده می‌شود. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | اطلاعات زمینهٔ مورد نیاز برای تجزیهٔ بخش XML. این اطلاعات می‌تواند شامل [XmlNameTable](../../xmlnametable/) برای استفاده، رمزگذاری، محدودهٔ فضای‌نام، محدودهٔ **xml:lang** و **xml:space** جاری، URI پایه و تعریف نوع سند باشد. این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از جریان مشخص و تنظیمات پیش‌فرض ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان حاوی داده‌های XML. [XmlReader](../) بایت‌های اولیهٔ جریان را برای یافتن علامت ترتیب بایت یا نشانهٔ دیگر رمزگذاری اسکن می‌کند. وقتی رمزگذاری تعیین شد، برای ادامهٔ خواندن جریان از آن استفاده می‌شود و پردازش به تجزیهٔ ورودی به عنوان یک جریان کاراکترهای (یونی‌کد) ادامه می‌دهد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) متد

یک نمونه جدید [XmlReader](../) با جریان و تنظیمات مشخص ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان حاوی داده‌های XML. [XmlReader](../) بایت‌های اولیهٔ جریان را برای یافتن علامت ترتیب بایت یا نشانهٔ دیگر رمزگذاری اسکن می‌کند. وقتی رمزگذاری تعیین شد، برای ادامهٔ خواندن جریان از آن استفاده می‌شود و پردازش به تجزیهٔ ورودی به عنوان یک جریان کاراکترهای (یونی‌کد) ادامه می‌دهد. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از جریان، URI پایه و تنظیمات ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان حاوی داده‌های XML. [XmlReader](../) بایت‌های اولیهٔ جریان را برای یافتن علامت ترتیب بایت یا نشانهٔ دیگر رمزگذاری اسکن می‌کند. وقتی رمزگذاری تعیین شد، برای ادامهٔ خواندن جریان از آن استفاده می‌شود و پردازش به تجزیهٔ ورودی به عنوان یک جریان کاراکترهای (یونی‌کد) ادامه می‌دهد. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |
| baseUri | const [String](../../../system/string/)\& | URI پایه برای موجودیت یا سندی که در حال خواندن است. این مقدار می‌تواند **nullptr** باشد. **[Security](../../../system.security/) Note** URI پایه برای حل URI نسبی سند XML استفاده می‌شود. از URI پایه‌ای که منبع غیرقابل اعتماد دارد استفاده نکنید. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از جریان، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان حاوی داده‌های XML. [XmlReader](../) بایت‌های اولیهٔ جریان را برای یافتن علامت ترتیب بایت یا نشانهٔ دیگر رمزگذاری اسکن می‌کند. وقتی رمزگذاری تعیین شد، برای ادامهٔ خواندن جریان از آن استفاده می‌شود و پردازش به تجزیهٔ ورودی به عنوان یک جریان کاراکترهای (یونی‌کد) ادامه می‌دهد. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | اطلاعات زمینهٔ مورد نیاز برای تجزیهٔ بخش XML. این اطلاعات می‌تواند شامل [XmlNameTable](../../xmlnametable/) برای استفاده، رمزگذاری، محدودهٔ فضای‌نام، محدودهٔ **xml:lang** و **xml:space** جاری، URI پایه و تعریف نوع سند باشد. این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از خوانندهٔ متنی مشخص ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | خوانندهٔ متنی که از آن داده‌های XML خوانده می‌شود. خوانندهٔ متنی یک جریان کاراکترهای یونی‌کد باز می‌گرداند، بنابراین رمزگذاری مشخص شده در اعلامیهٔ XML توسط خوانندهٔ XML برای رمزگشایی جریان داده استفاده نمی‌شود. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از خوانندهٔ متنی و تنظیمات مشخص ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | خوانندهٔ متنی که از آن داده‌های XML خوانده می‌شود. خوانندهٔ متنی یک جریان کاراکترهای یونی‌کد باز می‌گرداند، بنابراین رمزگذاری مشخص شده در اعلامیهٔ XML توسط خوانندهٔ XML برای رمزگشایی جریان داده استفاده نمی‌شود. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از خوانندهٔ متنی، تنظیمات و URI پایه ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | خوانندهٔ متنی که از آن داده‌های XML خوانده می‌شود. خوانندهٔ متنی یک جریان کاراکترهای یونی‌کد باز می‌گرداند، بنابراین رمزگذاری مشخص شده در اعلامیهٔ XML توسط [XmlReader](../) برای رمزگشایی جریان داده استفاده نمی‌شود. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |
| baseUri | const [String](../../../system/string/)\& | URI پایه برای موجودیت یا سندی که در حال خواندن است. این مقدار می‌تواند **nullptr** باشد. **[Security](../../../system.security/) Note** URI پایه برای حل URI نسبی سند XML استفاده می‌شود. از URI پایه‌ای که منبع غیرقابل اعتماد دارد استفاده نکنید. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) متد

یک نمونه جدید [XmlReader](../) با استفاده از خوانندهٔ متنی، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | خوانندهٔ متنی که از آن داده‌های XML خوانده می‌شود. خوانندهٔ متنی یک جریان کاراکترهای یونی‌کد باز می‌گرداند، بنابراین رمزگذاری مشخص شده در اعلامیهٔ XML توسط خوانندهٔ XML برای رمزگشایی جریان داده استفاده نمی‌شود. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | تنظیمات برای نمونهٔ جدید [XmlReader](../). این مقدار می‌تواند **nullptr** باشد. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | اطلاعات زمینهٔ مورد نیاز برای تجزیهٔ بخش XML. این اطلاعات می‌تواند شامل [XmlNameTable](../../xmlnametable/) برای استفاده، رمزگذاری، محدودهٔ فضای‌نام، محدودهٔ **xml:lang** و **xml:space** جاری، URI پایه و تعریف نوع سند باشد. این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

شیئی که برای خواندن داده‌های XML در جریان استفاده می‌شود.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) متد

یک نمونه جدید [XmlReader](../) با استفاده از خوانندهٔ XML مشخص و تنظیمات ایجاد می‌کند.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | شیئی که می‌خواهید به عنوان خوانندهٔ زیرین XML استفاده کنید. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | تنظیمات برای نمونهٔ جدید [XmlReader](../). سطح سازگاری شیء [XmlReaderSettings](../../xmlreadersettings/) باید یا با سطح سازگاری خوانندهٔ زیرین مطابقت داشته باشد یا به [ConformanceLevel::Auto](../../conformancelevel/) تنظیم شود. |

### مقدار بازگشت

شیئی که دور شیء [XmlReader](../) مشخص قرار داده شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlReader](../)
* کلاس [String](../../../system/string/)
* کلاس [XmlReaderSettings](../../xmlreadersettings/)
* کلاس [XmlParserContext](../../xmlparsercontext/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [TextReader](../../../system.io/textreader/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)