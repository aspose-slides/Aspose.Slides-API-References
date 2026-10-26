---
title: HighlightText()
second_title: Aspose.Slides for C++ API Referansı
description: Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.
type: docs
weight: 456
url: /tr/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) metod

Metin örneğinin tüm eşleşmelerini belirtilen renk ile vurgular.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için kullanılacak renk. |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunda metnin nasıl vurgulanacağını gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// tüm ayrı 'the' oluşumlarını vurgulama
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod

Metin örneğinin tüm eşleşmelerini belirtilen renk ile vurgular.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Vurgulanacak metin. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Metni vurgulamak için kullanılacak renk. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için kullanılan geri çağırma nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunda metnin nasıl vurgulanacağını gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// tüm ayrı 'the' oluşumlarını vurgulama
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IPresentation](../)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)