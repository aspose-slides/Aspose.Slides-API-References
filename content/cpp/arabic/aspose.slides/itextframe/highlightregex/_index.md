---
title: HighlightRegex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتمييز جميع التطابقات للتعبير النمطي باستخدام اللون المحدد.
type: docs
weight: 131
url: /ar/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) طريقة


يبرز جميع التطابقات للتعبير النمطي باستخدام اللون المحدد.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل لتسليط الضوء عليها. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات



يعرض عينة الكود التالية كيفية تمييز النص في [TextFrame](../../textframe/) باستخدام تعبير نمطي. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) طريقة


يبرز جميع التطابقات للتعبير النمطي باستخدام اللون المحدد.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | نص التعبير النمطي للحصول على النص لتسليط الضوء عليه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | خيارات التمييز. |

متقادم
:   استخدم طريقة HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) بدلاً من ذلك. سيتم إزالة الطريقة بعد إصدار النسخة 24.10.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Class [String](../../../system/string/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)