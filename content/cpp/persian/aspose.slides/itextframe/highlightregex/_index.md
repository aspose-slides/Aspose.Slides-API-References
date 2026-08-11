---
title: HighlightRegex()
second_title: Aspose.Slides برای مرجع API C++
description: تمام تطبیق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

تمام تطبیق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌های مورد برشماری. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ مورد استفاده برای برجسته‌سازی متن. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شی‌ء بازخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه می‌توان متن را در یک [TextFrame](../../textframe/) با استفاده از عبارت منظم برجسته کرد. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

تمام تطبیق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | متن عبارت منظم برای دریافت متنی که باید برجسته شود. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ مورد استفاده برای برجسته‌سازی متن. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | گزینه‌های برجسته‌سازی. |

منسوخ
:   به جای این روش از HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) استفاده کنید. این روش پس از انتشار نسخه 24.10 حذف خواهد شد.

## مراجعه کنید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Regex](../../../system.text.regularexpressions/regex/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* کلاس [ITextFrame](../)
* کلاس [String](../../../system/string/)
* کلاس [ITextHighlightingOptions](../../itexthighlightingoptions/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)