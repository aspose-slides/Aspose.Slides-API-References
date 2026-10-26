---
title: HighlightRegex()
second_title: مرجع API Aspose.Slides للغة C++
description: يبرز جميع التطابقات للتعبير النمطي باللون المحدد.
type: docs
weight: 157
url: /ar/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) طريقة

يُبرز جميع التطابقات للتعبير النمطي باللون المحدد.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### وسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | نص التعبير النمطي للحصول على النص لتسليط الضوء. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | خيارات التمييز. |
## ملاحظات

مهمل
:   استخدم طريقة HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) بدلاً من ذلك. سيتم إزالة الطريقة بعد إصدار النسخة 24.10.

يعرض مثال الشفرة التالي كيفية تمييز النص في [TextFrame](../) باستخدام تعبير نمطي. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// تسليط الضوء على جميع الكلمات التي تتكوّن من 10 أحرف أو أكثر
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) طريقة

يُبرز جميع التطابقات للتعبير النمطي باللون المحدد.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### وسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل لتسليط الضوء عليها. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات



يعرض مثال الشفرة التالي كيفية تمييز النص في [TextFrame](../) باستخدام تعبير نمطي. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// تسليط الضوء على جميع الكلمات التي تتكوّن من 10 أحرف أو أكثر
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Color](../../../system.drawing/color/)
* فئة [ITextHighlightingOptions](../../itexthighlightingoptions/)
* فئة [TextFrame](../)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)