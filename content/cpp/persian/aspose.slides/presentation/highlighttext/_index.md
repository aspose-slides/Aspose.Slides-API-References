---
title: HighlightText()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام مطابقت‌های متن نمونه را با رنگ مشخص‌شده برجسته می‌کند.
type: docs
weight: 495
url: /fa/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) متد

تمام مطابقت‌های متن نمونه را با رنگ مشخص‌شده برجسته می‌کند.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که متن را برجسته می‌کند. |
## توضیحات

نمونه کد زیر نشان می‌دهد چگونه متن را در یک ارائه PowerPoint برجسته کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// برجسته‌سازی تمام موارد جداگانه 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام مطابقت‌های متن نمونه را با رنگ مشخص‌شده برجسته می‌کند.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که متن را برجسته می‌کند. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء فراخوان برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |
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

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [Presentation](../)
* کلاس [ITextSearchOptions](../../itextsearchoptions/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)