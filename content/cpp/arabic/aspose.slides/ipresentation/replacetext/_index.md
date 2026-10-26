---
title: ReplaceText()
second_title: Aspose.Slides للغة C++ مرجع API
description: يستبدل جميع تكرارات النص المحدد بنص آخر محدد.
type: docs
weight: 482
url: /ar/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة

يستبدل جميع تكرارات النص المحدد بنص آخر محدد.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | السلسلة التي سيتم استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي ستحل محل جميع تكرارات oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات البحث النصي [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |
## ملاحظات

يعرض الكود النموذجي التالي كيفية استبدال سلسلة محددة بأخرى محددة.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// استبدال جميع تكرارات 'the' المنفصلة بـ '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [IPresentation](../)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)