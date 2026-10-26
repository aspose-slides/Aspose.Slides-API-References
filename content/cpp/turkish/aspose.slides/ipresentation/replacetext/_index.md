---
title: ReplaceText()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen metnin tüm örneklerini başka bir belirtilen metinle değiştirir.
type: docs
weight: 482
url: /tr/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metod

Belirtilen metnin tüm örneklerini başka bir belirtilen metinle değiştirir.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Değiştirilecek dize. |
| newText | [System::String](../../../system/string/) | oldText'in tüm örneklerini değiştirecek dize. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../ifindresultcallback/). |

## Açıklamalar

Aşağıdaki örnek kod, bir belirtilen dizeyi başka bir belirtilen dizeyle nasıl değiştireceğinizi gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Tüm ayrı 'the' örneklerini '<em><strong>' ile değiştir
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## İlgili Bilgiler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [IPresentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)