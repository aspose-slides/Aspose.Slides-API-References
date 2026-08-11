---
title: ReplaceRegex()
second_title: مرجع API Aspose.Slides برای C++
description: تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.
type: docs
weight: 183
url: /fa/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) متد


تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | The regular expression [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) to get strings to be replaced. |
| newText | [System::String](../../../system/string/) | The string to replace all occurrences of strings to be replaced. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback object for saving replacement operation result [IFindResultCallback](../../ifindresultcallback/). |
## توضیحات



کد نمونهٔ زیر نشان می‌دهد چگونه متن را با استفاده از عبارت منظم و رشتهٔ مشخص‌شده جایگزین کنیم. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Regex](../../../system.text.regularexpressions/regex/)
* کلاس [String](../../../system/string/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* کلاس [TextFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)