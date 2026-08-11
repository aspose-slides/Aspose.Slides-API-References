---
title: InsertFromHtml()
second_title: Aspose.Slides برای C++ مرجع API
description: اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.
type: docs
weight: 157
url: /fa/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء بازخوانی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::InsertFromHtml(int32_t, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء بازخوانی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به عنوان منبع فایل HTML استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | شیء Stream که به عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء بازخوانی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | شیء Stream که به عنوان منبع فایل HTML استفاده می‌شود. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج از اسلاید جدید یا از اسلاید با ایندکس مشخص شده آغاز شود. اگر **true** باشد، داده‌ها از فضای خالی در اسلاید با ایندکس مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء بازخوانی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج از اسلاید جدید یا از اسلاید با ایندکس مشخص شده آغاز شود. اگر **true** باشد، داده‌ها از فضای خالی در اسلاید با ایندکس مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | شیء Stream که به عنوان منبع فایل HTML استفاده می‌شود. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج از اسلاید جدید یا از اسلاید با ایندکس مشخص شده آغاز شود. اگر **true** باشد، داده‌ها از فضای خالی در اسلاید با ایندکس مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای اضافه شده

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) متد

اسلایدها را از متن HTML ایجاد می‌کند و در موقعیت مشخص به مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیت برای درج. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | شیء Stream که به عنوان منبع فایل HTML استفاده می‌شود. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء بازخوانی برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |
| useSlideWithIndexAsStart | **bool** | این پرچم تعیین می‌کند که درج از اسلاید جدید یا از اسلاید با ایندکس مشخص شده آغاز شود. اگر **true** باشد، داده‌ها از فضای خالی در اسلاید با ایندکس مشخص آغاز می‌شود. اگر **false** باشد، داده‌ها به اسلایدهای ایجاد شده اضافه می‌شوند. |

### مقدار بازگشت

اسلایدهای اضافه شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)