---
title: HighlightText()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.
type: docs
weight: 105
url: /tr/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) yöntemi

Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) yöntemi

Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Vurgulama seçenekleri. |

Kullanım dışı
:   Kullanın HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) yöntemi yerine. Bu yöntem, 24.10 sürümünden sonra kaldırılacaktır.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) yöntemi

Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için geri arama nesnesi [IFindResultCallback](../../ifindresultcallback/). |

## Açıklamalar

Aşağıdaki kod örneği, bir [TextFrame](../../textframe/) içinde metni nasıl vurgulayacağını gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [ITextFrame](../)
* Sınıf [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)