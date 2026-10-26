---
title: HighlightText()
second_title: مرجع API Aspose.Slides برای C++
description: تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند.
type: docs
weight: 456
url: /fa/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) متد

تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که برای برجسته‌سازی متن استفاده می‌شود. |
## توضیحات

نمونه کد زیر نشان می‌دهد چگونه متن را در یک ارائه PowerPoint برجسته کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// برجسته‌سازی تمام موارد جداگانه 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که برای برجسته‌سازی متن استفاده می‌شود. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء فراخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |
## توضیحات

نمونه کد زیر نشان می‌دهد چگونه متن را در یک ارائه PowerPoint برجسته کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// برجسته‌سازی تمام موارد جداگانه 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [IPresentation](../)
* کلاس [ITextSearchOptions](../../itextsearchoptions/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)