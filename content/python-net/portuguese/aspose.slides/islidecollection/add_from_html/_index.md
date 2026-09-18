---
title: add_from_html method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Cria slides a partir de texto HTML e os adiciona ao final da coleção.

### Retorna
Slides adicionados



```python
def add_from_html(self, html_text):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| html_text | **str** | HTML a ser adicionado. |


## add_from_html(self, html_stream) {#iorawiobase}
Cria slides a partir de texto HTML e os adiciona ao final da coleção.

### Retorna
Slides adicionados



```python
def add_from_html(self, html_stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Um objeto Stream que será usado como fonte de um arquivo HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Cria slides a partir de texto HTML e os adiciona ao final da coleção.

### Retorna
Slides adicionados.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| html_text | **str** | HTML a ser adicionado. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for None, todos os objetos externos serão ignorados. |
| uri | **str** | Um URI do HTML especificado. Usado para resolver links relativos. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Cria slides a partir de texto HTML e os adiciona ao final da coleção.

### Retorna
Slides adicionados.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for None, todos os objetos externos serão ignorados. |
| uri | **str** | Um URI do HTML especificado. Usado para resolver links relativos. |



### Ver também
* classe [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver)
* classe [`ISlideCollection`](/slides/python-net/pt/aspose.slides/islidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)