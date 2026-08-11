---
title: ReplaceRegex()
second_title: مرجع API Aspose.Slides برای C++
description: تمام تطابق‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) متد

تمام تطابق‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌هایی که باید جایگزین شوند. |
| newText | [System::String](../../../system/string/) | رشته‌ای برای جایگزینی تمام رخدادهای رشته‌های جایگزین‌شده. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء فراخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## توضیحات

نمونهٔ کدی که در زیر آمده نشان می‌دهد چگونه با استفاده از عبارت منظم متن را با رشتهٔ مشخص‌شده جایگزین کنیم. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)