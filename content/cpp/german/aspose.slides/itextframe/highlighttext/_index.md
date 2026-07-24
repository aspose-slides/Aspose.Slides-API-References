---
title: HighlightText()
second_title: Aspose.Slides für C++ API-Referenz
description: Markiert alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe.
type: docs
weight: 105
url: /de/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) method


Markiert alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu markierende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text markiert werden soll. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Markiert alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu markierende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text markiert werden soll. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Optionen für das Markieren. |

Veraltet
:   Verwenden Sie stattdessen die Methode HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback). Die Methode wird nach der Veröffentlichung von Version 24.10 entfernt.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Markiert alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der zu markierende Text. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text markiert werden soll. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Textsuchoptionen [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Rückrufobjekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |

## Anmerkungen



Das folgende Codebeispiel zeigt, wie man Text in einem [TextFrame](../../textframe/) hervorhebt. 
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [ITextFrame](../)
* Klasse [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)