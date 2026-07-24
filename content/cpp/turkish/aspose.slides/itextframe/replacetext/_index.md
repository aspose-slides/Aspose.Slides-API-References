---
title: ReplaceText()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir.
type: docs
weight: 144
url: /tr/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metot

Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Değiştirilecek dize. |
| newText | [System::String](../../../system/string/) | oldText'in tüm görünümlerini değiştirecek dize. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Arama sonuçlarını almak için geri arama nesnesi [IFindResultCallback](../../ifindresultcallback/). |

## Açıklamalar

Aşağıdaki örnek kod, bir belirtilen dizeyi başka bir belirtilen dizeyle nasıl değiştireceğini gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Tüm ayrı 'the' görünümlerini '<em><strong>' ile değiştir
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [ITextFrame](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)