---
title: HighlightRegex()
second_title: Aspose.Slides برای C++ API Reference
description: تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) متد

تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | متن عبارت منظم برای دریافت متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ برای برجسته کردن متن. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | گزینه‌های برجسته‌سازی. |
## توضیحات

منسوخ  
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.

نمونه کد زیر نشان می‌دهد چگونه می‌توان متن را در یک [TextFrame](../) با استفاده از یک عبارت منظم برجسته کرد. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// برجسته‌سازی تمام کلمات با ۱۰ یا بیشتر کاراکتر
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) متد

تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌های قابل برجسته‌سازی. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ برای برجسته کردن متن. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |
## توضیحات



نمونه کد زیر نشان می‌دهد چگونه می‌توان متن را در یک [TextFrame](../) با استفاده از یک عبارت منظم برجسته کرد. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// برجسته‌سازی تمام کلمات با ۱۰ یا بیشتر کاراکتر
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [ITextHighlightingOptions](../../itexthighlightingoptions/)
* کلاس [TextFrame](../)
* کلاس [Regex](../../../system.text.regularexpressions/regex/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)