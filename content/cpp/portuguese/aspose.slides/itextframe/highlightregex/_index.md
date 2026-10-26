---
title: HighlightRegex()
second_title: Referência da API Aspose.Slides para C++
description: Destaca todas as correspondências da expressão regular com a cor especificada.
type: docs
weight: 131
url: /pt/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) método

Destaca todas as correspondências da expressão regular com a cor especificada.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A expressão regular [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) para obter as strings a serem destacadas. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para destacar o texto. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber os resultados da pesquisa [IFindResultCallback](../../ifindresultcallback/). |
## Observações

O exemplo de código a seguir mostra como destacar texto em um [TextFrame](../../textframe/) usando uma expressão regular. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) método

Destaca todas as correspondências da expressão regular com a cor especificada.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Texto da expressão regular para obter o texto a ser destacado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para destacar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opções de destaque. |

Obsoleto
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) método em vez disso. O método será removido após o lançamento da versão 24.10.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [ITextFrame](../)
* Classe [String](../../../system/string/)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)