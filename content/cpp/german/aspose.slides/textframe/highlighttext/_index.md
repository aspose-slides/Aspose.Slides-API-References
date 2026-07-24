---
title: HighlightText()
second_title: Aspose.Slides für C++ API-Referenz
description: Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.
type: docs
weight: 131
url: /de/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) Methode

Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Textbeispiel zum Hervorheben. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe zum Hervorheben des Textes. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) Methode

Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu hervorhebende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe zum Hervorheben des Textes. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Optionen für das Hervorheben. |

## Hinweise

Veraltet
:   Verwenden Sie stattdessen die Methode HighlightText(string text, Color highlightColor, ITextSearchOptions options). Die Methode wird nach der Veröffentlichung der Version 24.10 entfernt.

Der folgende Beispielcode zeigt, wie man Text in einem [TextFrame](../) hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// Hervorheben aller Wörter 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// Hervorheben aller einzelnen Vorkommen von 'the'
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) Methode

Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu hervorhebende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe zum Hervorheben des Textes. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsuchoptionen [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |

## Hinweise

Das folgende Beispiel zeigt, wie man Text in einem [TextFrame](../) hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// Hervorheben aller Wörter 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Hervorheben aller einzelnen Vorkommen von 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [TextFrame](../)
* Klasse [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)