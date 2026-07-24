---
title: HighlightText()
second_title: Aspose.Slides for C++ API Referansı
description: Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.
type: docs
weight: 495
url: /tr/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) metod

Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunda metni nasıl vurgulayacağınızı gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// tüm ayrı 'the' oluşumlarını vurgulama
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod

Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için renk. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için geri arama nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunda metni nasıl vurgulayacağınızı gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// tüm ayrı 'the' oluşumlarını vurgulama
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [Presentation](../)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)