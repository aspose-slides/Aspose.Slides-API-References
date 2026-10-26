---
title: ReplaceText()
second_title: Aspose.Slides برای مرجع API C++
description: تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) متد

تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | رشته‌ای که باید جایگزین شود. |
| newText | [System::String](../../../system/string/) | رشته‌ای که تمام موارد oldText را جایگزین می‌کند. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | گزینه‌های جستجوی متن [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه یک رشته مشخص را با رشته دیگری که مشخص شده است جایگزین کنیم. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// تمام موارد جداگانه 'the' را با '<em><strong>' جایگزین کنید
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)