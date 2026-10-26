---
title: HighlightText()
second_title: Aspose.Slides pro C++ API Reference
description: Zvýrazní všechny výskyty ukázkového textu zvolenou barvou.
type: docs
weight: 105
url: /cs/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) metoda


Zvýrazní všechny výskyty ukázkového textu zvolenou barvou.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metoda


Zvýrazní všechny výskyty ukázkového textu zvolenou barvou.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Možnosti zvýrazňování. |

Zastaralé
:   Použijte HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) metodu místo toho. Metoda bude odstraněna po vydání verze 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda


Zvýrazní všechny výskyty ukázkového textu zvolenou barvou.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Možnosti vyhledávání textu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt pro zpětné volání přijímající výsledky vyhledávání [IFindResultCallback](../../ifindresultcallback/). |

## Poznámky



Následující ukázkový kód ukazuje, jak zvýraznit text v [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Color](../../../system.drawing/color/)
* Třída [ITextFrame](../)
* Třída [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Třída [ITextSearchOptions](../../itextsearchoptions/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)