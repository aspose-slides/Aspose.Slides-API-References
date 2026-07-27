---
title: ReplaceText()
second_title: Referência da API Aspose.Slides para C++
description: Substitui todas as ocorrências do texto especificado por outro texto especificado.
type: docs
weight: 482
url: /pt/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method

Substitui todas as ocorrências do texto especificado por outro texto especificado.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | A string a ser substituída. |
| newText | [System::String](../../../system/string/) | A string que substitui todas as ocorrências de oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opções de pesquisa de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber resultados da pesquisa [IFindResultCallback](../../ifindresultcallback/). |

## Observações

O código de exemplo a seguir mostra como substituir uma string especificada por outra string especificada. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Substitua todas as ocorrências separadas de 'the' por '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)