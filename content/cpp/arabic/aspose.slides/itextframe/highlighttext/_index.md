---
title: HighlightText()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُميّز جميع التطابقات للنص العيني باللون المحدد.
type: docs
weight: 105
url: /ar/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) طريقة

يُميّز جميع التطابقات للنص العيني باللون المحدد.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص لتسليط الضوء عليه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) طريقة

يُميّز جميع التطابقات للنص العيني باللون المحدد.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص لتسليط الضوء عليه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | خيارات التمييز. |

مهمل
:   استخدم طريقة HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) بدلاً من ذلك. ستُزال الطريقة بعد إصدار الإصدار 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة

يُميّز جميع التطابقات للنص العيني باللون المحدد.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص لتسليط الضوء عليه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون لتسليط الضوء على النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات بحث النص [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

يوضح مثال الشيفرة التالي كيفية تمييز النص في [TextFrame](../../textframe/). 
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

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الصنف [String](../../../system/string/)
* الصنف [Color](../../../system.drawing/color/)
* الصنف [ITextFrame](../)
* الصنف [ITextHighlightingOptions](../../itexthighlightingoptions/)
* الصنف [ITextSearchOptions](../../itextsearchoptions/)
* الصنف [IFindResultCallback](../../ifindresultcallback/)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)