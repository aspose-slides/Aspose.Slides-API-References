---
title: ReplaceRegex()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem znaków.
type: docs
weight: 495
url: /pl/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metoda

Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem znaków.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Wyrażenie regularne [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) służące do pobierania ciągów do zamiany. |
| newText | [System::String](../../../system/string/) | Ciąg znaków służący do zastąpienia wszystkich wystąpień ciągów do zamiany. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Obiekt zwrotny służący do odbierania wyników wyszukiwania [IFindResultCallback](../../ifindresultcallback/). |

## Uwagi

Poniższy przykładowy kod pokazuje, jak zastąpić tekst przy użyciu wyrażenia regularnego i podanego ciągu znaków.

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Regex](../../../system.text.regularexpressions/regex/)
* Klasa [String](../../../system/string/)
* Klasa [IFindResultCallback](../../ifindresultcallback/)
* Klasa [IPresentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)