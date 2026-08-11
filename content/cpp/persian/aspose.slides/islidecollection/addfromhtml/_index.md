---
title: AddFromHtml()
second_title: Aspose.Slides برای C++ مرجع API
description: اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.
type: docs
weight: 144
url: /fa/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء بازخوانی استفاده می‌شود برای دریافت اشیای خارجی. اگر این پارامتر null باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::AddFromHtml(System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء بازخوانی استفاده می‌شود برای دریافت اشیای خارجی. اگر این پارامتر null باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به عنوان منبع یک فایل HTML استفاده خواهد شد. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء بازخوانی استفاده می‌شود برای دریافت اشیای خارجی. اگر این پارامتر null باشد تمام اشیای خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |

### مقدار بازگشت

اسلایدهای اضافه شده

## همچنین ببینید

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [String](../../../system/string/)
* کلاس [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* کلاس [ISlideCollection](../)
* کلاس [TextReader](../../../system.io/textreader/)
* کلاس [Stream](../../../system.io/stream/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)