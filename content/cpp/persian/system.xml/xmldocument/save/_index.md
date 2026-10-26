---
title: Save()
second_title: مرجع API Aspose.Slides برای C++
description: سند XML را در فایلی که مشخص شده ذخیره می‌کند. اگر فایل مشخص‌شده وجود داشته باشد، این متد آن را بازنویسی می‌کند.
type: docs
weight: 534
url: /fa/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) متد


Saves the XML document to the specified file. If the specified file exists, this method overwrites it.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | [String](../../../system/string/) | محل فایلی که می‌خواهید سند را در آن ذخیره کنید. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) متد


Saves the XML document to the specified stream.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که می‌خواهید در آن ذخیره کنید. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) متد


Saves the XML document to the specified TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter که می‌خواهید در آن ذخیره کنید. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) متد


Saves the XML document to the specified [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | [XmlWriter](../../xmlwriter/) که می‌خواهید در آن ذخیره کنید. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [TextWriter](../../../system.io/textwriter/)
* کلاس [XmlWriter](../../xmlwriter/)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)