---
title: ReplaceText()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem.
type: docs
weight: 144
url: /pl/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda


Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Ciąg znaków do zastąpienia. |
| newText | [System::String](../../../system/string/) | Ciąg znaków, który zastępuje wszystkie wystąpienia oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opcje wyszukiwania tekstu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |
## Uwagi



Poniższy przykładowy kod pokazuje, jak zastąpić jeden określony ciąg innym określonym ciągiem. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Zastąp wszystkie oddzielne wystąpienia 'the' ciągiem '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ITextSearchOptions](../../itextsearchoptions/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Klasa [ITextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)