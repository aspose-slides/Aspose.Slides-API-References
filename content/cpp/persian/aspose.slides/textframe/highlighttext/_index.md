---
title: HighlightText()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) متد

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نمونه متن برای برجسته‌سازی. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ برای برجسته‌سازی متن. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) متد

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن برای برجسته‌سازی. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ برای برجسته‌سازی متن. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | گزینه‌های برجسته‌سازی. |

## توضیحات

منقضی
:   به جای آن از HighlightText(string text, Color highlightColor, ITextSearchOptions options) متد استفاده کنید. این متد پس از انتشار نسخه 24.10 حذف خواهد شد.

کد نمونه زیر نحوه برجسته‌سازی متن را در یک [TextFrame](../) نشان می‌دهد. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن برای برجسته‌سازی. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ برای برجسته‌سازی متن. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه متن را در یک [TextFrame](../) برجسته کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// برجسته‌سازی تمام کلمات 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// برجسته‌سازی تمام رخدادهای جداگانه 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [TextFrame](../)
* کلاس [ITextHighlightingOptions](../../itexthighlightingoptions/)
* کلاس [ITextSearchOptions](../../itextsearchoptions/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)