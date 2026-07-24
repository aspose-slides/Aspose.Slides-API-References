---
title: ReplaceRegex()
second_title: Aspose.Slides için C++ API Referansı
description: Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir.
type: docs
weight: 495
url: /tr/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) yöntemi

Düzenli ifadenin tüm eşleşmelerini belirtilen dizgeyle değiştirir.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) düzenli ifadesi, değiştirilecek dizeleri elde etmek için kullanılır. |
| newText | [System::String](../../../system/string/) | Değiştirilecek tüm dize örneklerini değiştirmek için kullanılan dize. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | [IFindResultCallback](../../ifindresultcallback/) arama sonuçlarını almak için geri arama nesnesi. |

## Açıklamalar

Aşağıdaki kod örneği, düzenli ifade kullanarak metni belirtilen dizgeyle nasıl değiştireceğinizi gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [String](../../../system/string/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [IPresentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)