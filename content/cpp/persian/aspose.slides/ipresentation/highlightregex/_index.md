---
title: HighlightRegex()
second_title: Aspose.Slides برای مرجع API C++
description: تمام موارد مطابقت عبارت منظم را با رنگ مشخص شده برجسته می‌کند.
type: docs
weight: 469
url: /fa/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

تمام موارد مطابقت عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌های برای برجسته‌کردن. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگ برای برجسته کردن متن. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

نمونه کد زیر نشان می‌دهد که چگونه متن را در یک PowerPoint [Presentation](../../presentation/) با استفاده از یک عبارت منظم برجسته کنید.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)