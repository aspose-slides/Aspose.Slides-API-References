---
title: ReplaceRegex()
second_title: Aspose.Slides لـ C++ مرجع API
description: يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.
type: docs
weight: 534
url: /ar/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) طريقة

يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل التي سيتم استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي تُستبدل جميع ظهورات السلاسل التي يجب استبدالها. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن الاستدعاء الراجع لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

توضح عينة الشيفرة التالية كيفية استبدال النص باستخدام التعبير النمطي مع السلسلة المحددة.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [String](../../../system/string/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [Presentation](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)