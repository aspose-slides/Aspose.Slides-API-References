---
title: HighlightText()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.
type: docs
weight: 131
url: /tr/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) metod

Belirtilen renkle örnek metnin tüm eşleşmelerini vurgular.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text sample to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metod

Belirtilen renkle örnek metnin tüm eşleşmelerini vurgular.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | The text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Highlighting options. |

## Açıklamalar

Kullanımdan kaldırıldı:   HighlightText(string text, Color highlightColor, ITextSearchOptions options) metodunu kullanın. Metod, 24.10 sürümünün yayınlanmasının ardından kaldırılacak.

Aşağıdaki örnek kod, bir [TextFrame](../) içinde Metni Vurgulamanın nasıl yapılacağını gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// tüm 'important' kelimelerini vurgulama
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// tüm ayrı 'the' oluşumlarını vurgulama
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod

Belirtilen renkle örnek metnin tüm eşleşmelerini vurgular.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | The text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Text search options [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | The callback object for receiving search results [IFindResultCallback](../../ifindresultcallback/). |

## Açıklamalar



Aşağıdaki kod örneği, bir [TextFrame](../) içinde metni nasıl vurgulayacağını gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// tüm 'important' kelimelerini vurgulama
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// tüm ayrı 'the' oluşumlarını vurgulama
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [TextFrame](../)
* Sınıf [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)