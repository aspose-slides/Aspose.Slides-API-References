---
title: HighlightText()
second_title: مرجع API برای Aspose.Slides به زبان C++
description: تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.
type: docs
weight: 105
url: /fa/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) متد

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که متن باید با آن برجسته شود. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) متد

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که متن باید با آن برجسته شود. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | گزینه‌های برجسته‌سازی. |

منسوخ
:   به جای آن از متد HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) استفاده کنید. این متد پس از انتشار نسخه 24.10 حذف خواهد شد.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی که متن باید با آن برجسته شود. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء بازگشتی برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## توضیح

نمونه کد زیر نشان می‌دهد چگونه متن را در یک [TextFrame](../../textframe/) برجسته کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [ITextFrame](../)
* کلاس [ITextHighlightingOptions](../../itexthighlightingoptions/)
* کلاس [ITextSearchOptions](../../itextsearchoptions/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* فضای‌نامی [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)