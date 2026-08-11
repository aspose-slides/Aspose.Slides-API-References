---
title: ReplaceText()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.
type: docs
weight: 170
url: /fa/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | رشته‌ای که باید جایگزین شود. |
| newText | [System::String](../../../system/string/) | رشته‌ای که تمام موارد oldText را جایگزین می‌کند. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شی Callback برای ذخیره نتیجهٔ عملیات جایگزینی [IFindResultCallback](../../ifindresultcallback/). |

## توضیحات

کد نمونه زیر نشان می‌دهد که چگونه یک رشتهٔ مشخص را با رشتهٔ مشخص دیگری جایگزین کنیم.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// تمام موارد جداگانهٔ 'the' را با '<em><strong>' جایگزین می‌کند
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ITextSearchOptions](../../itextsearchoptions/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* کلاس [TextFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)