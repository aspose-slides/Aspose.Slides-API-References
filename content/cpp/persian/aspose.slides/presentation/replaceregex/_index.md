---
title: ReplaceRegex()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.
type: docs
weight: 534
url: /fa/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) متد


عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌هایی که باید جایگزین شوند. |
| newText | [System::String](../../../system/string/) | رشته‌ای برای جایگزینی تمام رخدادهای رشته‌های قابل جایگزینی. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |
## توضیحات



نمونه کد زیر نشان می‌دهد چگونه متن را با استفاده از عبارت منظم با رشتهٔ مشخص شده جایگزین کنیم. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Regex](../../../system.text.regularexpressions/regex/)
* کلاس [String](../../../system/string/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)