---
title: ReplaceRegex()
second_title: Referência da API Aspose.Slides for C++
description: Substitui todas as correspondências da expressão regular pela string especificada.
type: docs
weight: 534
url: /pt/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) método


Substitui todas as correspondências da expressão regular pela string especificada.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A expressão regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obter strings a serem substituídas. |
| newText | [System::String](../../../system/string/) | A string para substituir todas as ocorrências das strings a serem substituídas. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de callback para receber os resultados da pesquisa [IFindResultCallback](../../ifindresultcallback/). |
## Observações



O exemplo de código a seguir mostra como substituir texto usando expressão regular com a string especificada. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [String](../../../system/string/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)