---
title: ReplaceRegex()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenfolge.
type: docs
weight: 157
url: /de/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) Methode

Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenfolge.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) zum Erhalten der zu ersetzenden Zeichenfolgen. |
| newText | [System::String](../../../system/string/) | Die Zeichenfolge, die alle Vorkommen der zu ersetzenden Zeichenfolgen ersetzt. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |
## Hinweise

Das folgende Codebeispiel zeigt, wie Text mithilfe eines regulären Ausdrucks durch die angegebene Zeichenfolge ersetzt wird.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [String](../../../system/string/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [ITextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)