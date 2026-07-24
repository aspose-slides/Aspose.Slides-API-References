---
title: ReplaceRegex()
second_title: Aspose.Slides für C++ API Referenz
description: Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenfolge.
type: docs
weight: 183
url: /de/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) Methode


Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenfolge.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) zum Ermitteln der zu ersetzenden Zeichenfolgen. |
| newText | [System::String](../../../system/string/) | Die Zeichenfolge, mit der alle Vorkommen der zu ersetzenden Zeichenfolgen ersetzt werden. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback-Objekt zum Speichern des Ergebnisses der Ersetzungsoperation [IFindResultCallback](../../ifindresultcallback/). |
## Anmerkungen



Der folgende Beispielcode zeigt, wie Text mit einem regulären Ausdruck durch eine angegebene Zeichenfolge ersetzt wird. 
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
* Klasse [TextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)