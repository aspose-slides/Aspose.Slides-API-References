---
title: ReplaceText()
second_title: مرجع API Aspose.Slides برای C++
description: تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.
type: docs
weight: 482
url: /fa/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | رشته‌ای که باید جایگزین شود. |
| newText | [System::String](../../../system/string/) | رشته‌ای که تمام موارد oldText را جایگزین می‌کند. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## توضیحات

کد نمونه زیر نشان می‌دهد که چگونه یک رشته مشخص را با رشته دیگری که مشخص شده است جایگزین کنید.

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// جایگزینی تمام موارد جداگانهٔ 'the' با '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ITextSearchOptions](../../itextsearchoptions/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* کلاس [IPresentation](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)