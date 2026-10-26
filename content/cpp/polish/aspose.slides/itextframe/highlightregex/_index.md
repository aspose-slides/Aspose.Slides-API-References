---
title: HighlightRegex()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.
type: docs
weight: 131
url: /pl/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metoda


Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Wyrażenie regularne [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) służące do uzyskania ciągów znaków do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor służący do podświetlenia tekstu. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt zwrotny służący do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |
## Uwagi



Poniższy przykład kodu pokazuje, jak podświetlić tekst w [TextFrame](../../textframe/) przy użyciu wyrażenia regularnego. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// podświetlanie wszystkich słów mających 10 lub więcej znaków
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metoda


Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Tekst wyrażenia regularnego służący do uzyskania tekstu do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor służący do podświetlenia tekstu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opcje podświetlania. |

Przestarzałe
:   Użyj zamiast tego metody HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Metoda zostanie usunięta po wydaniu wersji 24.10.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Regex](../../../system.text.regularexpressions/regex/)
* Klasa [Color](../../../system.drawing/color/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Klasa [ITextFrame](../)
* Klasa [String](../../../system/string/)
* Klasa [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)