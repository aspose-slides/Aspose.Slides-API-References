---
title: Deserialize()
second_title: Aspose.Slides برای C++ مرجع API
description: سند XML را به شیء بازسازی می‌کند.
type: docs
weight: 14
url: /fa/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) متد

سند XML را به شیء بازسازی می‌کند.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریان برای خواندن سند. |

### مقدار بازگشتی

[Object](../../../system/object/) که قبلاً در سند ارائه‌شده سریالیزه شده بود.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) متد

سند XML را به شیء بازسازی می‌کند.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | خوانشگر برای خواندن سند. |

### مقدار بازگشتی

[Object](../../../system/object/) که قبلاً در سند ارائه‌شده سریالیزه شده بود.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) متد

سند XML را به شیء بازسازی می‌کند.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | خوانشگر برای خواندن سند. |

### مقدار بازگشتی

[Object](../../../system/object/) که قبلاً در سند ارائه‌شده سریالیزه شده بود.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) متد

سند XML را به شیء بازسازی می‌کند.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | خوانشگر برای خواندن سند. |
| encodingStyle | [String](../../../system/string/) | سبکی که برای سریالیزه کردن شیء استفاده می‌شود. |

### مقدار بازگشتی

[Object](../../../system/object/) که قبلاً در سند ارائه‌شده سریالیزه شده بود.

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [XmlSerializer](../)
* کلاس [TextReader](../../../system.io/textreader/)
* کلاس [XmlReader](../../../system.xml/xmlreader/)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::Serialization](../../)
* کتابخانه [Aspose.Slides](../../../)