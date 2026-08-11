---
title: HighlightText()
second_title: Aspose.Slides للغة C++ مرجع API
description: يُبرز جميع التطابقات للنص النموذجي باللون المحدد.
type: docs
weight: 495
url: /ar/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) method


يبرز جميع التطابقات للنص النموذجي باللون المحدد.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص المراد تمييزه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |
## ملاحظات



يعرض مثال الشيفرة التالي كيفية تمييز النص في عرض تقديمي PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// تمييز جميع ظهورات 'the' المنفصلة
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


يبرز جميع التطابقات للنص النموذجي باللون المحدد.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص المراد تمييزه. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | اللون المستخدم لتمييز النص. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات بحث النص [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات



يعرض مثال الشيفرة التالي كيفية تمييز النص في عرض تقديمي PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// تمييز جميع ظهورات 'the' المنفصل
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Color](../../../system.drawing/color/)
* فئة [Presentation](../)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)