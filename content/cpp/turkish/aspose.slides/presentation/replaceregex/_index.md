---
title: ReplaceRegex()
second_title: Aspose.Slides için C++ API Referansı
description: Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir.
type: docs
weight: 534
url: /tr/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) yöntemi


Düzenli ifadenin tüm eşleşmelerini belirtilen dizgeyle değiştirir.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) düzenli ifadesi, değiştirilmesi gereken dizgeleri elde etmek için kullanılır. |
| newText | [System::String](../../../system/string/) | Değiştirilecek dizgelerin tüm oluşumlarını değiştirecek dizge. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | [IFindResultCallback](../../ifindresultcallback/) arama sonuçlarını almak için geri çağırma nesnesi. |
## Açıklamalar



Aşağıdaki kod örneği, düzenli ifade kullanarak metni belirtilen dizgeyle nasıl değiştireceğinizi gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [String](../../../system/string/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)