---
title: HighlightText()
second_title: مرجع API Aspose.Slides للغة C++
description: يُبرز جميع التطابقات للنص العيني باللون المحدد.
type: docs
weight: 456
url: /ar/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) طريقة

يقوم بتمييز جميع التطابقات للنص العيني باللون المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص المراد تمييزه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |
## ملاحظات

يعرض مثال الشيفرة التالي كيفية تمييز النص في عرض تقديمي PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// تمييز جميع حدوثات 'the' المنفصلة
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة

يقوم بتمييز جميع التطابقات للنص العيني باللون المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص المراد تمييزه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات البحث النصية [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات

يعرض مثال الشيفرة التالي كيفية تمييز النص في عرض تقديمي PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// تمييز جميع حدوثات 'the' المنفصلة
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Color](../../../system.drawing/color/)
* فئة [IPresentation](../)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)