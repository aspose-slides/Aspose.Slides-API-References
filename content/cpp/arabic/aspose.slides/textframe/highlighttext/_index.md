---
title: HighlightText()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يميز جميع التطابقات للنص العيني باللون المحدد.
type: docs
weight: 131
url: /ar/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) طريقة


يميز جميع التطابقات للنص العيني باللون المحدد.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | عينة النص للتمييز. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) طريقة


يميز جميع التطابقات للنص العيني باللون المحدد.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص المراد تمييزه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | خيارات التمييز. |
## ملاحظات


مهمل
:   استخدم طريقة HighlightText(string text, Color highlightColor, ITextSearchOptions options) بدلاً من ذلك. ستتم إزالة الطريقة بعد إصدار النسخة 24.10.


يعرض الشيفرة النموذجية التالية كيفية تمييز النص في [TextFrame](../). 
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

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة


يميز جميع التطابقات للنص العيني باللون المحدد.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص المراد تمييزه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات البحث عن النص [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء للحصول على نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات



يعرض الشيفرة النموذجية التالية كيفية تمييز النص في [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// تمييز جميع الكلمات 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// تمييز جميع حدوثات 'the' المنفصلة
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Color](../../../system.drawing/color/)
* فئة [TextFrame](../)
* فئة [ITextHighlightingOptions](../../itexthighlightingoptions/)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)