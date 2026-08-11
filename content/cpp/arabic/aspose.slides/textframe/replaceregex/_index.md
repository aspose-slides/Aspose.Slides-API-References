---
title: ReplaceRegex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.
type: docs
weight: 183
url: /ar/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) طريقة

يستبدل جميع مطابقات التعبير النمطي بالسلسلة المحددة.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل التي سيتم استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة لاستبدال جميع حالات السلاسل التي سيتم استبدالها. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد النداء لحفظ نتيجة عملية الاستبدال [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

يظهر الكود النموذجي التالي كيف يتم استبدال النص باستخدام التعبير النمطي مع سلسلة محددة. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [String](../../../system/string/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [TextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)