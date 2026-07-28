---
title: HighlightRegex()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.
type: docs
weight: 469
url: /pl/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metoda

Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Wyrażenie regularne [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) służące do pobierania ciągów do podświetlenia. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Kolor służący do podświetlenia tekstu. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |

## Uwagi

Poniższy przykład kodu pokazuje, jak podświetlić tekst w PowerPoint [Presentation](../../presentation/) przy użyciu wyrażenia regularnego. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Regex](../../../system.text.regularexpressions/regex/)
* Klasa [Color](../../../system.drawing/color/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Klasa [IPresentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)