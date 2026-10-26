---
title: ReplaceRegex()
second_title: Aspose.Slides pro C++ API Reference
description: Nahradí všechny výskyty regulárního výrazu zadaným řetězcem.
type: docs
weight: 534
url: /cs/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

Nahradí všechny výskyty regulárního výrazu zadaným řetězcem.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Regulární výraz [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pro získání řetězců k nahrazení. |
| newText | [System::String](../../../system/string/) | Řetězec pro nahrazení všech výskytů řetězců, které mají být nahrazeny. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků hledání [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky

Následující ukázkový kód ukazuje, jak nahradit text pomocí regulárního výrazu zadaným řetězcem.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Nahradí všechna slova s 10 a více znaky řetězcem '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Regex](../../../system.text.regularexpressions/regex/)
* Třída [String](../../../system/string/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)