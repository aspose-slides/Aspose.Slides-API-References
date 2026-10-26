---
title: XmlTextReader()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس XmlTextReader را با جریان مشخص شده مقداردهی اولیه می‌کند.
type: docs
weight: 482
url: /fa/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با جریان مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که شامل داده‌های XML برای خواندن است. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با URL و جریان مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL مورد استفاده برای حل منابع خارجی. [XmlTextReader::get_BaseURI](../get_baseuri/) به این مقدار تنظیم می‌شود. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که شامل داده‌های XML برای خواندن است. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با جریان و [XmlNameTable](../../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که شامل داده‌های XML برای خواندن است. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) مورد استفاده. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با URL، جریان و [XmlNameTable](../../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL مورد استفاده برای حل منابع خارجی. [XmlTextReader::get_BaseURI](../get_baseuri/) به این مقدار تنظیم می‌شود. اگر **url** برابر **nullptr** باشد، **BaseURI** برابر [String::Empty](../../../system/string/empty/) تنظیم می‌شود. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که شامل داده‌های XML برای خواندن است. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) مورد استفاده. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با TextReader مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader حاوی داده‌های XML برای خواندن. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با URL و TextReader مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL مورد استفاده برای حل منابع خارجی. [XmlTextReader::get_BaseURI](../get_baseuri/) به این مقدار تنظیم می‌شود. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader حاوی داده‌های XML برای خواندن. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با TextReader و [XmlNameTable](../../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader حاوی داده‌های XML برای خواندن. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) مورد استفاده. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با URL، TextReader و [XmlNameTable](../../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL مورد استفاده برای حل منابع خارجی. [XmlTextReader::get_BaseURI](../get_baseuri/) به این مقدار تنظیم می‌شود. اگر **url** برابر **nullptr** باشد، **BaseURI** برابر [String::Empty](../../../system/string/empty/) تنظیم می‌شود. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader حاوی داده‌های XML برای خواندن. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) مورد استفاده. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با جریان، XmlNodeType و [XmlParserContext](../../xmlparsercontext/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریانی که شامل بخش XML برای تجزیه است. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType بخش XML. این مقدار تعیین می‌کند بخش چه محتوایی می‌تواند داشته باشد. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/)ی که **xmlFragment** در آن تجزیه می‌شود. این شامل [XmlNameTable](../../xmlnametable/) مورد استفاده، رمزگذاری، محدوده فضای نام، **xml:lang** فعلی و محدوده **xml:space** می‌باشد. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با رشته، XmlNodeType و [XmlParserContext](../../xmlparsercontext/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | رشته‌ای که شامل بخش XML برای تجزیه است. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType بخش XML. این مقدار تعیین می‌کند رشته بخش چه محتوایی می‌تواند داشته باشد. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/)ی که **xmlFragment** در آن تجزیه می‌شود. این شامل [XmlNameTable](../../xmlnametable/) مورد استفاده، رمزگذاری، محدوده فضای نام، **xml:lang** فعلی و محدوده **xml:space** می‌باشد. |

## XmlTextReader::XmlTextReader(const String\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با فایل مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL فایلی که شامل داده‌های XML است. [XmlTextReader::get_BaseURI](../get_baseuri/) به این مقدار تنظیم می‌شود. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) سازنده

یک نمونه جدید از کلاس [XmlTextReader](../) را با فایل و [XmlNameTable](../../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL فایلی که شامل داده‌های XML برای خواندن است. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) مورد استفاده. |

## موارد مرتبط

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)