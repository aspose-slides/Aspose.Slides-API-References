---
title: ReplaceRegex()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizeyle düzenli ifadenin tüm eşleşmelerini değiştirir.
type: docs
weight: 157
url: /tr/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metot


Belirtilen dizeyle düzenli ifadeye ait tüm eşleşmeleri değiştirir.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Değiştirilecek dizeleri elde etmek için kullanılacak düzenli ifade [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| newText | [System::String](../../../system/string/) | Değiştirilecek dizelerin tüm oluşumlarını değiştirecek dize. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için kullanılan geri arama nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar



Aşağıdaki kod örneği, düzenli ifade kullanarak metni belirtilen dizeyle nasıl değiştireceğinizi gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [String](../../../system/string/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [ITextFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)