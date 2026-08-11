---
title: ReplaceRegex()
second_title: Aspose.Slides لـ C++ مرجع API
description: يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.
type: docs
weight: 157
url: /ar/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل التي سيتم استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي ستستبدل جميع تكرارات السلاسل التي سيتم استبدالها. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد النداء لاستلام نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

يعرض المثال البرمجي التالي كيفية استبدال النص باستخدام التعبير النمطي مع السلسلة المحددة. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [String](../../../system/string/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [ITextFrame](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)