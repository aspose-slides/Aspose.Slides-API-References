---
title: HighlightText()
second_title: Aspose.Slides pro C++ – reference API
description: Zvýrazní všechny výskyty vzorového textu zadanou barvou.
type: docs
weight: 495
url: /cs/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) metoda

Zvýrazní všechny výskyty vzorového textu určenou barvou.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |
## Poznámky

Následující ukázkový kód ukazuje, jak zvýraznit text v PowerPoint prezentaci. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// zvýraznění všech samostatných výskytů 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda

Zvýrazní všechny výskyty vzorového textu určenou barvou.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Možnosti hledání textu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro získávání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky

Následující ukázkový kód ukazuje, jak zvýraznit text v PowerPoint prezentaci. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// zvýraznění všech samostatných výskytů 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Color](../../../system.drawing/color/)
* Třída [Presentation](../)
* Třída [ITextSearchOptions](../../itextsearchoptions/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)