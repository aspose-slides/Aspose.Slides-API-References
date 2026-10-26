---
title: ReplaceRegex()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nahradí všechny shody regulárního výrazu zadaným řetězcem.
type: docs
weight: 495
url: /cs/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metoda


Nahrazuje všechny shody regulárního výrazu zadaným řetězcem.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Regulární výraz [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pro získání řetězců k nahrazení. |
| newText | [System::String](../../../system/string/) | Řetězec, který nahradí všechny výskyty řetězců, jež mají být nahrazeny. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky



Následující ukázkový kód ukazuje, jak nahradit text pomocí regulárního výrazu zadaným řetězcem.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Regex](../../../system.text.regularexpressions/regex/)
* Třída [String](../../../system/string/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Třída [IPresentation](../)
* Název prostoru [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)