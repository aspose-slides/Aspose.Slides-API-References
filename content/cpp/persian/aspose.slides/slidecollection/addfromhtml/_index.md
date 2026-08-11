---
title: AddFromHtml()
second_title: مرجع API Aspose.Slides برای C++
description: اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.
type: docs
weight: 196
url: /fa/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء کال‌بک مورد استفاده برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

### مقدار بازگشتی

اسلایدهای اضافه شده.

## SlideCollection::AddFromHtml(System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML برای افزودن. |

### مقدار بازگشتی

اسلایدهای اضافه شده.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء کال‌بک مورد استفاده برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

### مقدار بازگشتی

اسلایدهای اضافه شده.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | شیء TextReader که به عنوان منبع یک فایل HTML استفاده خواهد شد. |

### مقدار بازگشتی

اسلایدهای اضافه شده.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء کال‌بک مورد استفاده برای دریافت اشیاء خارجی. اگر این پارامتر null باشد تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| uri | [System::String](../../../system/string/) | یک URI از HTML مشخص‌شده. برای حل لینک‌های نسبی استفاده می‌شود. |

### مقدار بازگشتی

اسلایدهای اضافه شده.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) متد

اسلایدها را از متن HTML ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | شیء Stream که به عنوان منبع یک فایل HTML استفاده خواهد شد. |

### مقدار بازگشتی

اسلایدهای اضافه شده.

## ملاحظات

```cpp
// یک نمونه از کلاس Presentation ایجاد کنید.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // متد AddFromHtml را فراخوانی کنید و فایل HTML را پاس دهید.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// از متد Save برای ذخیره فایل به صورت سند PowerPoint استفاده کنید.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [String](../../../system/string/)
* کلاس [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* کلاس [SlideCollection](../)
* کلاس [TextReader](../../../system.io/textreader/)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)