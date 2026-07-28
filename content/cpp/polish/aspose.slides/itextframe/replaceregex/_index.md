---
title: ReplaceRegex()
second_title: Aspose.Slides dla C++ - Referencja API
description: Zastępuje wszystkie dopasowania wyrażenia regularnego podanym łańcuchem znaków.
type: docs
weight: 157
url: /pl/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metoda

Zastępuje wszystkie dopasowania wyrażenia regularnego podanym łańcuchem znaków.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Wyrażenie regularne [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) określające ciągi do zastąpienia. |
| newText | [System::String](../../../system/string/) | Łańcuch znaków służący do zastąpienia wszystkich wystąpień ciągów do zastąpienia. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |
## Uwagi

Poniższy przykład kodu pokazuje, jak zastąpić tekst przy użyciu wyrażenia regularnego podanym łańcuchem znaków.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Regex](../../../system.text.regularexpressions/regex/)
* Klasa [String](../../../system/string/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Klasa [ITextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)