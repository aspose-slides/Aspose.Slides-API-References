---
title: ReplaceRegex()
second_title: Referência da API Aspose.Slides para C++
description: Substitui todas as ocorrências da expressão regular pela string especificada.
type: docs
weight: 495
url: /pt/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) método


Substitui todas as ocorrências da expressão regular pela string especificada.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A expressão regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obter strings a serem substituídas. |
| newText | [System::String](../../../system/string/) | A string que substitui todas as ocorrências das strings a serem substituídas. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber os resultados da pesquisa [IFindResultCallback](../../ifindresultcallback/). |
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
* Classe [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)