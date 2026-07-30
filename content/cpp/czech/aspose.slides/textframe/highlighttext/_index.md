---
title: HighlightText()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Zvýrazní všechny výskyty ukázkového textu zadanou barvou.
type: docs
weight: 131
url: /cs/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) metoda

Zvýrazní všechny výskyty ukázkového textu zadanou barvou.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Textová ukázka k zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metoda

Zvýrazní všechny výskyty ukázkového textu zadanou barvou.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text k zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Možnosti zvýraznění. |

## Poznámky

Zastaralé
:   Použijte místo toho metodu HighlightText(string text, Color highlightColor, ITextSearchOptions options). Metoda bude odstraněna po vydání verze 24.10.

Následující ukázkový kód ukazuje, jak zvýraznit text v [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda

Zvýrazní všechny výskyty ukázkového textu zadanou barvou.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text k zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Možnosti vyhledávání textu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |

## Poznámky



Následující ukázkový kód ukazuje, jak zvýraznit text v [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// zvýraznění všech slov 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// zvýraznění všech samostatných výskytů 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [String](../../../system/string/)
* třída [Color](../../../system.drawing/color/)
* třída [TextFrame](../)
* třída [ITextHighlightingOptions](../../itexthighlightingoptions/)
* třída [ITextSearchOptions](../../itextsearchoptions/)
* třída [IFindResultCallback](../../ifindresultcallback/)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)