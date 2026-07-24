---
title: ReplaceText()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen metnin tüm tekrarlarını başka bir belirtilen metinle değiştirir.
type: docs
weight: 521
url: /tr/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod


Belirtilen metnin tüm tekrarlarını başka bir belirtilen metinle değiştirir.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Değiştirilecek dize. |
| newText | [System::String](../../../system/string/) | oldText'in tüm tekrarlarını değiştirecek dize. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar



Aşağıdaki örnek kod, bir belirtilen dizeyi başka bir belirtilen dizeyle nasıl değiştireceğinizi gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Tüm ayrı 'the' tekrarlarını '<em><strong>' ile değiştir.
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)