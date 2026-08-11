---
title: ReplaceRegex()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستبدل جميع التطابقات للعبارة النمطية بالسلسلة المحددة.
type: docs
weight: 495
url: /ar/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) طريقة

يستبدل جميع التطابقات للعبارة النمطية بالسلسلة المحددة.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | التعبير النمطي [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) للحصول على السلاسل المراد استبدالها. |
| newText | [System::String](../../../system/string/) | السلسلة التي تستبدل جميع حالات السلاسل المراد استبدالها. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../ifindresultcallback/). |

## ملاحظات

يعرض مثال الشيفرة التالي كيفية استبدال النص باستخدام التعبير النمطي مع السلسلة المحددة. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Regex](../../../system.text.regularexpressions/regex/)
* فئة [String](../../../system/string/)
* فئة [IFindResultCallback](../../ifindresultcallback/)
* فئة [IPresentation](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)