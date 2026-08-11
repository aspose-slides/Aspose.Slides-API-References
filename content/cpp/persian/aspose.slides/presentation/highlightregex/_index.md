---
title: HighlightRegex()
second_title: مرجع API Aspose.Slides برای C++
description: تمام تطبیق‌های عبارت منظم را با رنگ مشخص‌شده برجسته می‌کند.
type: docs
weight: 508
url: /fa/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) متد


تمام تطبیق‌های عبارت منظم را با رنگ مشخص‌شده برجسته می‌کند.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | عبارت منظم [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) برای دریافت رشته‌های قابل برجسته‌سازی. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | رنگی برای برجسته‌سازی متن. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../ifindresultcallback/). |
## توضیحات



نمونه کد زیر نشان می‌دهد چگونه می‌توان متن را در یک [Presentation](../) پاورپوینت با استفاده از یک عبارت منظم برجسته کرد.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// برجسته‌سازی تمام کلمات با 10 یا بیشتر کاراکتر
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Regex](../../../system.text.regularexpressions/regex/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [IFindResultCallback](../../ifindresultcallback/)
* کلاس [Presentation](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)