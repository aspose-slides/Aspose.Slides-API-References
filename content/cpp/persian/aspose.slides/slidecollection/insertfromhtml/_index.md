---
title: InsertFromHtml()
second_title: مرجع API Aspose.Slides برای C++
description: اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.
type: docs
weight: 209
url: /fa/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای افزوده شده.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج چگونه آغاز شود: از یک اسلاید جدید یا از اسلایدی با شاخص مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با شاخص مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای افزوده شده.

## SlideCollection::InsertFromHtml(int32_t, System::String) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |

### مقدار بازگشت

اسلایدهای افزوده شده

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج چگونه آغاز شود: از یک اسلاید جدید یا از اسلایدی با شاخص مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با شاخص مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای افزوده شده

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به‌عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای افزوده شده.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به‌عنوان منبع یک فایل HTML استفاده خواهد شد. |

### مقدار بازگشت

اسلایدهای افزوده شده

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک شیء Stream که به‌عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای افزوده شده.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک شیء Stream که به‌عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | یک شیء callback که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج چگونه آغاز شود: از یک اسلاید جدید یا از اسلایدی با شاخص مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با شاخص مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای افزوده شده.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک شیء Stream که به‌عنوان منبع یک فایل HTML استفاده خواهد شد. |

### مقدار بازگشت

اسلایدهای افزوده شده

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) متد


اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که باید در آن درج شود. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک شیء Stream که به‌عنوان منبع یک فایل HTML استفاده خواهد شد. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج چگونه آغاز شود: از یک اسلاید جدید یا از اسلایدی با شاخص مشخص. اگر **true** باشد، درج داده‌ها از یک فضای خالی در اسلاید با شاخص مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای افزوده شده

## همچنین ببینید

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [String](../../../system/string/)
* کلاس [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* کلاس [SlideCollection](../)
* کلاس [TextReader](../../../system.io/textreader/)
* کلاس [Stream](../../../system.io/stream/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)