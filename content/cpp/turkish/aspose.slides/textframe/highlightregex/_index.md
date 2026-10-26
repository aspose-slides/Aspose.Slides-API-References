---
title: HighlightRegex()
second_title: C++ için Aspose.Slides API Referansı
description: Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular.
type: docs
weight: 157
url: /tr/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) yöntemi

Belirtilen renk ile düzenli ifadeye ait tüm eşleşmeleri vurgular.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Vurgulanacak metni elde etmek için düzenli ifade metni. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Vurgulama seçenekleri. |

## Açıklamalar

Kullanımdan kaldırıldı
:   HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) yöntemini kullanın.

Aşağıdaki kod örneği, bir düzenli ifade kullanarak [TextFrame](../) içinde metni nasıl vurgulayacağınızı gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// 10 veya daha fazla karaktere sahip tüm kelimeleri vurgulama
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) yöntemi

Belirtilen renk ile düzenli ifadeye ait tüm eşleşmeleri vurgular.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Vurgulamak için dizeleri elde etmek amacıyla kullanılan [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) düzenli ifadesi. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını [IFindResultCallback](../../ifindresultcallback/) almak için geri çağırma nesnesi. |

## Açıklamalar



Aşağıdaki kod örneği, bir düzenli ifade kullanarak [TextFrame](../) içinde metni nasıl vurgulayacağınızı gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// 10 veya daha fazla karaktere sahip tüm kelimeleri vurgulama
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Sınıf [TextFrame](../)
* Sınıf [Regex](../../../system.text.regularexpressions/regex/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)