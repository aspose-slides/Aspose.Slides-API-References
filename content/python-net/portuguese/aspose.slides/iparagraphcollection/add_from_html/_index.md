---
title: add_from_html method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iparagraphcollection/add_from_html/
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
| text | **str** | texto HTML. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Adiciona texto de uma string HTML especificada à coleção.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| text | **str** | texto HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Objeto de callback do resolvedor que resolve URIs e obtém objetos referenciados. |
| uri | **str** | URI para adicionar o documento HTML. Usado para resolver links relativos. |

### Observações

Especificar o resolvedor pode potencialmente introduzir uma vulnerabilidade. Use com cautela.

### Ver também
* classe [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver)
* classe [`IParagraphCollection`](/slides/python-net/pt/aspose.slides/iparagraphcollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)