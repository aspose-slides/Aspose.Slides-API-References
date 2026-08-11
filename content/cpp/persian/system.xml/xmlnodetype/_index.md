---
title: XmlNodeType
second_title: مرجع API Aspose.Slides برای C++
description: نوع گره را مشخص می‌کند.
type: docs
weight: 833
url: /fa/system.xml/xmlnodetype/
---
## XmlNodeType enum

Specifies the type of node.

```cpp
enum class XmlNodeType
```

### مقادیر

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | این مقدار توسط [XmlReader](../xmlreader/) بازگردانده می‌شود اگر متد **Read** فراخوانی نشده باشد. |
| Element | 1 | یک عنصر (به عنوان مثال **<item>**). |
| Attribute | 2 | یک ویژگی (به عنوان مثال **id='123'**). |
| Text | 3 | محتوای متنی یک گره. یک گره [XmlNodeType::Text](./) نمی‌تواند هیچ گره فرزندی داشته باشد. می‌تواند به عنوان گره فرزند گره‌های [XmlNodeType::Attribute](./)، [XmlNodeType::DocumentFragment](./)، [XmlNodeType::Element](./) و [XmlNodeType::EntityReference](./) ظاهر شود. |
| CDATA | 4 | یک بخش CDATA (به عنوان مثال **my escaped text**). |
| EntityReference | 5 | یک ارجاع به یک موجودیت (به عنوان مثال **&num;**). |
| Entity | 6 | یک اعلان موجودیت (به عنوان مثال **<!ENTITY...>**). |
| ProcessingInstruction | 7 | یک دستور پردازش (به عنوان مثال **<?pi test?>**). |
| Comment | 8 | یک نظر (به عنوان مثال ****). |
| Document | 9 | یک شی سند که به عنوان ریشه‌ی درخت سند، دسترسی به کل سند XML را فراهم می‌کند. |
| DocumentType | 10 | اعلان نوع سند که با تگ زیر نشان داده می‌شود (به عنوان مثال **<!DOCTYPE...>**). |
| DocumentFragment | 11 | یک تکه سند. |
| Notation | 12 | یک نماد در اعلان نوع سند (به عنوان مثال **<!NOTATION...>**). |
| Whitespace | 13 | فاصله‌گذاری بین نشانه‌ها. |
| SignificantWhitespace | 14 | فاصله‌گذاری بین نشانه‌ها در یک مدل محتوا ترکیبی یا فاصله‌گذاری در محدوده **xml:space="preserve"**. |
| EndElement | 15 | یک تگ پایان عنصر (به عنوان مثال ****). |
| EndEntity | 16 | در زمانی که [XmlReader](../xmlreader/) به انتهای جایگزینی موجودیت می‌رسد به‌عنوان نتیجه‌ای از فراخوانی [XmlReader::ResolveEntity](../xmlreader/resolveentity/) برگردانده می‌شود. |
| XmlDeclaration | 17 | اعلان XML (به عنوان مثال **<?xml version='1.0'?>**). گره [XmlNodeType::XmlDeclaration](./) باید اولین گره در سند باشد. نمی‌تواند فرزند داشته باشد. این گره فرزند گره [XmlNodeType::Document](./) است. می‌تواند ویژگی‌هایی داشته باشد که اطلاعات نسخه و رمزگذاری را فراهم می‌آورند. |

## موارد مرتبط

* فضا‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)