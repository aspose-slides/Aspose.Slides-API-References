---
title: HighlightRegex()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.
type: docs
weight: 157
url: /pl/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Tekst wyrażenia regularnego służącego do podświetlenia tekstu. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor używany do podświetlenia tekstu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opcje podświetlania. |
## Uwagi


Przestarzałe
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.


Poniższy przykład kodu pokazuje, jak podświetlić tekst w [TextFrame](../) przy użyciu wyrażenia regularnego. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// podświetlanie wszystkich słów o długości 10 lub więcej znaków
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Wyrażenie regularne [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) do uzyskania ciągów do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor używany do podświetlenia tekstu. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |
## Uwagi



Poniższy przykład kodu pokazuje, jak podświetlić tekst w [TextFrame](../) przy użyciu wyrażenia regularnego. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// podświetlanie wszystkich słów o długości 10 lub więcej znaków
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)