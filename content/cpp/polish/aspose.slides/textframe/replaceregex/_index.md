---
title: ReplaceRegex()
second_title: Aspose.Slides dla C++ Referencja API
description: Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem znaków.
type: docs
weight: 183
url: /pl/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metoda

Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem znaków.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Wyrażenie regularne [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) służące do uzyskania ciągów znaków do zastąpienia. |
| newText | [System::String](../../../system/string/) | Ciąg znaków służący do zastąpienia wszystkich wystąpień ciągów znaków do zastąpienia. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt zwrotny służący do zapisywania wyniku operacji zastąpienia [IFindResultCallback](../../ifindresultcallback/). |

## Uwagi

Poniższy kod przykładowy pokazuje, jak zastąpić tekst przy użyciu wyrażenia regularnego podanym ciągiem znaków.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Regex](../../../system.text.regularexpressions/regex/)
* Klasa [String](../../../system/string/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Klasa [TextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)