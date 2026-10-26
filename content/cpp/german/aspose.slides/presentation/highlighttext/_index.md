---
title: HighlightText()
second_title: Aspose.Slides für C++ API-Referenz
description: Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor.
type: docs
weight: 495
url: /de/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) Methode

Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der Text, der hervorgehoben werden soll. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text hervorgehoben wird. |
## Bemerkungen

Das folgende Codebeispiel zeigt, wie man Text in einer PowerPoint-Präsentation hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Hervorheben aller separaten 'the'-Vorkommen
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) Methode

Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Der Text, der hervorgehoben werden soll. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text hervorgehoben wird. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Optionen für die Textsuche [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |
## Bemerkungen

Das folgende Codebeispiel zeigt, wie man Text in einer PowerPoint-Präsentation hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Hervorheben aller separaten 'the'-Vorkommen
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [Presentation](../)
* Klasse [ITextSearchOptions](../../itextsearchoptions/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)