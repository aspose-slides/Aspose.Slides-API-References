---
title: XmlValidatingReader()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس XmlValidatingReader را مقداردهی اولیه می‌کند که محتویات بازگردانده‌شده از XmlReader داده شده را اعتبارسنجی می‌نماید.
type: docs
weight: 430
url: /fa/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) سازنده

یک نمونه جدید از کلاس [XmlValidatingReader](../) که محتوای بازگردانده شده از [XmlReader](../../xmlreader/) داده شده را اعتبارسنجی می‌کند، مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) برای خواندن در حین اعتبارسنجی. پیاده‌سازی فعلی فقط [XmlTextReader](../../xmltextreader/) را پشتیبانی می‌کند. |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) سازنده

یک نمونه جدید از کلاس [XmlValidatingReader](../) با مقادیر مشخص‌شده مقداردهی اولیه می‌شود.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | رشته‌ای حاوی قطعه XML برای تجزیه. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType قطعه XML. این همچنین تعیین می‌کند که رشته قطعه چه محتوایی می‌تواند داشته باشد (به جدول زیر مراجعه کنید). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) که در آن قطعه XML باید تجزیه شود. این شامل [NameTable](../../nametable/) مورد استفاده، رمزگذاری، محدوده فضای نام، **xml:lang** فعلی و محدوده **xml:space** می‌باشد. |

## توضیحات

جدول زیر مقادیر معتبر برای **fragType** و نحوه تجزیه خواننده برای هر یک از انواع گره‌های مختلف را فهرست می‌کند.

| XmlNodeType | محتوای مجاز |
| --- | --- |
| Element| هر محتوای معتبر عنصر (به عنوان مثال، ترکیبی از عناصر، نظرات، دستورهای پردازشی، cdata، متن و مراجع موجودیت). |
| [Attribute](../../../system/attribute/)| مقدار یک ویژگی (بخشی که داخل نقل‌قول‌ها قرار دارد). |
| Document| محتوای یک سند XML کامل؛ این قوانین سطح سند را اعمال می‌کند. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) سازنده

یک نمونه جدید از کلاس [XmlValidatingReader](../) با مقادیر مشخص‌شده مقداردهی اولیه می‌شود.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان حاوی قطعه XML برای تجزیه. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType قطعه XML. این تعیین می‌کند که قطعه چه محتوایی می‌تواند داشته باشد (به جدول زیر مراجعه کنید). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) که در آن قطعه XML باید تجزیه شود. این شامل [XmlNameTable](../../xmlnametable/) مورد استفاده، رمزگذاری، محدوده فضای نام، **xml:lang** فعلی و محدوده **xml:space** می‌باشد. |

## توضیحات

جدول زیر مقادیر معتبر برای **fragType** و نحوه تجزیه خواننده برای هر یک از انواع گره‌های مختلف را فهرست می‌کند.

| XmlNodeType | محتوای مجاز |
| --- | --- |
| Element| هر محتوای معتبر عنصر (به عنوان مثال، ترکیبی از عناصر، نظرات، دستورهای پردازشی, cdata, متن و مراجع موجودیت). |
| [Attribute](../../../system/attribute/)| مقدار یک ویژگی (بخشی که داخل نقل‌قول‌ها قرار دارد). |
| Document| محتوای یک سند XML کامل؛ این قوانین سطح سند را اعمال می‌کند. |

## مراجع

* شمارشی [XmlNodeType](../../xmlnodetype/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlReader](../../xmlreader/)
* کلاس [XmlValidatingReader](../)
* کلاس [String](../../../system/string/)
* کلاس [XmlParserContext](../../xmlparsercontext/)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)