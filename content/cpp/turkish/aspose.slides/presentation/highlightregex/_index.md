---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.
type: docs
weight: 508
url: /tr/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metodu


Belirtilen renk ile düzenli ifadeye uyan tüm eşleşmeleri vurgular.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) düzenli ifadesi, vurgulanacak dizeleri almak için kullanılır. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için geri arama nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar



Aşağıdaki kod örneği, bir PowerPoint [Presentation](../) içinde düzenli ifade kullanarak metni nasıl vurgulayacağınızı gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// 10 veya daha fazla karaktere sahip tüm kelimeleri vurgulama
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## İlgili Bilgiler

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [Presentation](../)
* Ad Alanı [Aspose::Slides](../../)
* Kitaplık [Aspose.Slides](../../../)