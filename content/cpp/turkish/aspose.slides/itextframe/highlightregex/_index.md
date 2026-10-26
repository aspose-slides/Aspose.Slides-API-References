---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.
type: docs
weight: 131
url: /tr/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metod


Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Vurgulanacak dizeleri elde etmek için kullanılan düzenli ifade [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/). |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için kullanılan renk. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için kullanılan geri çağırma nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklama



Aşağıdaki kod örneği, bir [TextFrame](../../textframe/) içinde düzenli ifade kullanarak metnin nasıl vurgulanacağını gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metod


Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Vurgulanacak metni elde etmek için kullanılan düzenli ifadenin metni. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için kullanılan renk. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Vurgulama seçenekleri. |

Kullanımdan Kaldırılmış
:   Bunun yerine HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) metodunu kullanın. Bu metod, sürüm 24.10 yayımlandıktan sonra kaldırılacaktır.

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [ITextFrame](../)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)