---
title: IsStartElement()
second_title: مرجع API Aspose.Slides برای C++
description: "متد XmlReader::MoveToContent را فراخوانی می‌کند و بررسی می‌کند که گره محتوای فعلی یک تگ شروع یا تگ عنصر خالی باشد."
type: docs
weight: 885
url: /fa/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() متد

[XmlReader::MoveToContent](../movetocontent/) را فراخوانی می‌کند و بررسی می‌کند که گره محتوای فعلی یک تگ شروع یا تگ عنصر خالی باشد.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### مقدار بازگشت

**true** اگر [XmlReader::MoveToContent](../movetocontent/) یک تگ شروع یا تگ عنصر خالی پیدا کند؛ **false** اگر نوع گره‌ای غیر از [XmlNodeType::Element](../../xmlnodetype/) یافت شود.

## XmlReader::IsStartElement(String) متد

[XmlReader::MoveToContent](../movetocontent/) را فراخوانی می‌کند و بررسی می‌کند که گره محتوای فعلی یک تگ شروع یا تگ عنصر خالی باشد و آیا مقدار [XmlReader::get_Name](../get_name/) عنصر پیدا شده با آرگومان داده شده مطابقت دارد.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| name | [String](../../../system/string/) | رشته‌ای که با مقدار **Name** عنصر یافت‌شده مطابقت دارد. |

### مقدار بازگشت

**true** اگر گره حاصل یک عنصر باشد و مقدار **Name** با رشته‌ی مشخص شده مطابقت داشته باشد؛ **false** اگر نوع گره‌ای غیر از [XmlNodeType::Element](../../xmlnodetype/) یافت شود یا مقدار **Name** عنصر با رشته‌ی مشخص شده مطابقت نداشته باشد.

## XmlReader::IsStartElement(String, String) متد

[XmlReader::MoveToContent](../movetocontent/) را فراخوانی می‌کند و بررسی می‌کند که گره محتوای فعلی یک تگ شروع یا تگ عنصر خالی باشد و مقادیر [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) عنصر پیدا شده با رشته‌های داده‌شده مطابقت داشته باشند.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| localname | [String](../../../system/string/) | رشته‌ای برای مقایسه با مقدار **LocalName** عنصر یافت‌شده. |
| ns | [String](../../../system/string/) | رشته‌ای برای مقایسه با مقدار **NamespaceURI** عنصر یافت‌شده. |

### مقدار بازگشت

**true** اگر گره حاصل یک عنصر باشد. **false** اگر نوع گره‌ای غیر از [XmlNodeType::Element](../../xmlnodetype/) یافت شود یا مقادیر **LocalName** و **NamespaceURI** عنصر با رشته‌های مشخص‌شده مطابقت نداشته باشند.

## مراجع

* کلاس [XmlReader](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)