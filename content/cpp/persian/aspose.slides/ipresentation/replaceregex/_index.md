---
title: ReplaceRegex()
second_title: مرجع API Aspose.Slides برای C++
description: تمام تطابق‌های عبارت منظم را با رشته‌ی مشخص شده جایگزین می‌کند.
type: docs
weight: 495
url: /fa/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) متد


عبارت منظم را با رشتهٔ مشخص شده جایگزین می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌هایی که باید جایگزین شوند. |
| newText | [System::String](../../../system/string/) | رشته‌ای برای جایگزینی تمام موارد رشته‌های قابل جایگزینی. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |
## توضیحات



نمونه کد زیر نشان می‌دهد چگونه متن را با استفاده از عبارت منظم و رشتهٔ مشخص شده جایگزین کنید. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)