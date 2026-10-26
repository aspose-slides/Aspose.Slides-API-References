---
title: AddFromHtml()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona texto a partir da string HTML especificada à coleção.
type: docs
weight: 157
url: /pt/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) método


Adiciona texto a partir da string HTML especificada à coleção.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texto HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método


Adiciona texto a partir da string HTML especificada à coleção.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texto HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objeto de callback do resolvedor que resolve URIs e busca objetos referenciados. |
| uri | [System::String](../../../system/string/) | URI para adicionar o documento HTML. Usado para resolver links relativos. |
## Observações



Especificar o resolver pode potencialmente introduzir uma vulnerabilidade. Use com cautela.
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ParagraphCollection](../)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)