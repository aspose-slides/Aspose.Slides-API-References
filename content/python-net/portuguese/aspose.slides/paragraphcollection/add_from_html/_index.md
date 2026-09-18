---
title: add_from_html method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Adiciona texto de uma string HTML especificada à coleção.

```python
def add_from_html(self, text):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| text | **str** | Texto HTML. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Adiciona texto de uma string HTML especificada à coleção.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| text | **str** | Texto HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Objeto de retorno de chamada do resolvedor que resolve URIs e obtém os objetos referenciados. |
| uri | **str** | URI para adicionar o documento HTML. Usado para resolver links relativos. |

### Observações

Especificar o resolvedor pode potencialmente introduzir uma vulnerabilidade. Use com cautela.

### Veja Também
* classe [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver)
* classe [`ParagraphCollection`](/slides/python-net/pt/aspose.slides/paragraphcollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)