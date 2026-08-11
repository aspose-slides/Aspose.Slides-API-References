---
title: ReplaceText()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يستبدل جميع حدوث النص المحدد بنص آخر محدد.
type: docs
weight: 521
url: /ar/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) طريقة

يستبدل جميع حدوث النص المحدد بنص محدد آخر.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | السلسلة التي سيتم استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي ستحل محل جميع حدوث oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | خيارات البحث النصي [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

يوضح الكود النموذجي التالي كيفية استبدال سلسلة محددة بأخرى محددة. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// استبدل جميع حدوثات 'the' المنفصلة بـ '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ITextSearchOptions](../../itextsearchoptions/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [Presentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)