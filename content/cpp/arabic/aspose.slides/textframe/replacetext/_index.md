---
title: ReplaceText()
second_title: Aspose.Slides مرجع API للغة C++
description: يستبدل جميع تكرارات النص المحدد بنص آخر محدد.
type: docs
weight: 170
url: /ar/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة


يستبدل جميع حدوث النص المحدد بنص محدد آخر.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | السلسلة التي سيتم استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي ستستبدل جميع حدوث oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات بحث النص [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد الاتصال لحفظ نتيجة عملية الاستبدال [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات



يعرض الكود النموذجي التالي كيفية استبدال سلسلة محددة بأخرى محددة. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// استبدال جميع حدوثات كلمة 'the' المنفصلة بـ '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [TextFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)