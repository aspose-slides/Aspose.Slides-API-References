---
title: HighlightRegex()
second_title: Referência da API Aspose.Slides para C++
description: Realça todas as correspondências da expressão regular com a cor especificada.
type: docs
weight: 508
url: /pt/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) método

Realça todas as correspondências da expressão regular com a cor especificada.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A expressão regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obter strings a realçar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber resultados de pesquisa [IFindResultCallback](../../ifindresultcallback/). |
## Observações

O exemplo de código a seguir mostra como realçar texto em um PowerPoint [Presentation](../) usando uma expressão regular.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)