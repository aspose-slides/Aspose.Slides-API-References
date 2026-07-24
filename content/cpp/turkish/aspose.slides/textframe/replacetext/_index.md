---
title: ReplaceText()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir.
type: docs
weight: 170
url: /tr/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metodu


Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Değiştirilecek dize. |
| newText | [System::String](../../../system/string/) | oldText'in tüm oluşumlarını değiştirecek dize. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Metin arama seçenekleri [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Değiştirme işlemi sonucunu kaydetmek için geri çağırma nesnesi [IFindResultCallback](../../ifindresultcallback/). |
## Açıklamalar



Aşağıdaki örnek kod, bir belirli dizeyi başka bir belirli dizeyle nasıl değiştireceğini gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Tüm ayrı 'the' oluşumlarını '<em><strong>' ile değiştir
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextSearchOptions](../../itextsearchoptions/)
* Sınıf [IFindResultCallback](../../ifindresultcallback/)
* Sınıf [TextFrame](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)