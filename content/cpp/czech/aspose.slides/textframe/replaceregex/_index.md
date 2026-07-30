---
title: ReplaceRegex()
second_title: Aspose.Slides pro C++ API Reference
description: Nahradí všechny shody regulárního výrazu zadaným řetězcem.
type: docs
weight: 183
url: /cs/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metoda


Nahradí všechny shody regulárního výrazu zadaným řetězcem.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Regulární výraz [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pro získání řetězců, které mají být nahrazeny. |
| newText | [System::String](../../../system/string/) | Řetězec, který nahradí všechny výskyty řetězců, jež mají být nahrazeny. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro uložení výsledku operace nahrazení [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky



Následující ukázkový kód ukazuje, jak nahradit text pomocí regulárního výrazu zadaným řetězcem. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Regex](../../../system.text.regularexpressions/regex/)
* Třída [String](../../../system/string/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Třída [TextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)