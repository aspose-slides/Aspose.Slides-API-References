---
title: AddFromHtml()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona texto a partir da string HTML especificada à coleção.
type: docs
weight: 92
url: /pt/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) método

Adiciona texto a partir da string HTML especificada à coleção.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Adiciona texto a partir da string HTML especificada à coleção.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objeto de callback do resolvedor que resolve URIs e obtém objetos referenciados. |
| uri | [System::String](../../../system/string/) | URI para adicionar o documento HTML. Usado para resolver links relativos. |

## Observações

Especificar o resolvedor pode potencialmente introduzir uma vulnerabilidade. Use com cautela.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IParagraphCollection](../)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)