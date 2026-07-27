---
title: ReplaceText()
second_title: Aspose.Slides para C++ Referência da API
description: Substitui todas as ocorrências do texto especificado por outro texto especificado.
type: docs
weight: 144
url: /pt/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método

Substitui todas as ocorrências do texto especificado por outro texto especificado.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | A string a ser substituída. |
| newText | [System::String](../../../system/string/) | A string que substitui todas as ocorrências de oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opções de pesquisa de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber resultados de pesquisa [IFindResultCallback](../../ifindresultcallback/). |

## Observações

O código de exemplo a seguir mostra como substituir uma string especificada por outra string especificada.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Substitui todas as ocorrências separadas de 'the' por '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [ITextFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)