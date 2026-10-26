---
title: ReplaceRegex()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen dizeyle düzenli ifadenin tüm eşleşmelerini değiştirir.
type: docs
weight: 183
url: /tr/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metodu

Belirtilen dizgeyle düzenli ifadenin tüm eşleşmelerini değiştirir.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Değiştirilecek dizgeleri elde etmek için [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) düzenli ifadesi. |
| newText | [System::String](../../../system/string/) | Değiştirilecek dizgelerin tüm örneklerini değiştirecek dize. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Değiştirme işlemi sonucunu kaydetmek için geri çağırma nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar

Aşağıdaki örnek kod, düzenli ifade kullanarak metni belirtilen dizgeyle nasıl değiştireceğinizi gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)