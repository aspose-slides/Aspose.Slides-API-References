---
title: Load()
second_title: مرجع API Aspose.Slides برای C++
description: سند XML را از URL مشخص شده بارگذاری می‌کند.
type: docs
weight: 508
url: /fa/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) متد

سند XML را از URL مشخص شده بارگذاری می‌کند.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL برای فایلی که سند XML را در خود دارد و باید بارگذاری شود. URL می‌تواند یک فایل محلی یا یک URL HTTP (آدرسی [Web](../../../system.web/)) باشد. |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) متد

سند XML را از جریان مشخص شده بارگذاری می‌کند.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که سند XML را در خود دارد و باید بارگذاری شود. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) متد

سند XML را از TextReader مشخص شده بارگذاری می‌کند.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader استفاده شده برای تزریق داده‌های XML به سند. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) متد

سند XML را از [XmlReader](../../xmlreader/) مشخص شده بارگذاری می‌کند.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) استفاده شده برای تزریق داده‌های XML به سند. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [TextReader](../../../system.io/textreader/)
* کلاس [XmlReader](../../xmlreader/)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)