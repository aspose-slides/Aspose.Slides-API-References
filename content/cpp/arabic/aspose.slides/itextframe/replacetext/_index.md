---
title: ReplaceText()
second_title: مرجع API Aspose.Slides للغة C++
description: يستبدل جميع مرات الظهور للنص المحدد بنص آخر محدد.
type: docs
weight: 144
url: /ar/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة

يستبدل جميع تكرارات النص المحدد بنص آخر محدد.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | السلسلة المراد استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي ستستبدل جميع تكرارات oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات البحث النصي [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد الاتصال لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات

يعرض مثال الشيفرة التالي كيفية استبدال سلسلة محددة بأخرى محددة.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// استبدال جميع تكرارات 'the' المستقلة بـ '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [ITextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)