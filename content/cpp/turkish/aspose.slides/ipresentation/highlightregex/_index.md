---
title: HighlightRegex()
second_title: C++ için Aspose.Slides API Referansı
description: Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.
type: docs
weight: 469
url: /tr/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Vurgulanacak dizeleri almak için kullanılan düzenli ifade [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını [IFindResultCallback](../../ifindresultcallback/) almak için geri çağırma nesnesi. |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint [Presentation](../../presentation/) içinde düzenli ifade kullanarak metni nasıl vurgulayacağınızı gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// 10 veya daha fazla karaktere sahip tüm kelimeleri vurgulama
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [IPresentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)