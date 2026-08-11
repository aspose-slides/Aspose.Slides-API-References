---
title: Read()
second_title: مرجع API Aspose.Slides برای C++
description: "یک XML Schema را از IO::TextReader ارائه‌شده می‌خواند."
type: docs
weight: 365
url: /fa/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method


یک XML [Schema](../../) را از [IO::TextReader](../../../system.io/textreader/) ارائه‌شده می‌خواند.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/) حاوی XML [Schema](../../) برای خواندن. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | رویداد هندلر اعتبارسنجی که اطلاعات دربارهٔ خطاهای نحوی XML [Schema](../../) دریافت می‌کند. |

### مقدار بازگشت

شیء [XmlSchema](../) که نمایانگر XML [Schema](../../) است.

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method


یک XML [Schema](../../) را از جریان ارائه‌شده می‌خواند.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان دادهٔ ارائه‌شده. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | رویداد هندلر اعتبارسنجی که اطلاعات دربارهٔ خطاهای نحوی XML [Schema](../../) دریافت می‌کند. |

### مقدار بازگشت

شیء [XmlSchema](../) که نمایانگر XML [Schema](../../) است.

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method


یک XML [Schema](../../) را از [XmlReader](../../../system.xml/xmlreader/) ارائه‌شده می‌خواند.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) حاوی XML [Schema](../../) برای خواندن. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | رویداد هندلر اعتبارسنجی که اطلاعات دربارهٔ خطاهای نحوی XML [Schema](../../) دریافت می‌کند. |

### مقدار بازگشت

شیء [XmlSchema](../) که نمایانگر XML [Schema](../../) است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)