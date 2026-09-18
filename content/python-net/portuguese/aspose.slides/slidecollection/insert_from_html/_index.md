---
title: insert_from_html method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_text | **str** | Html a ser adicionado. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_stream | **io.RawIOBase** | Um objeto Stream que será usado como fonte de um arquivo HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_text | **str** | Html a ser adicionado. |
| use_slide_with_index_as_start | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado.<br/><br/>            Se **true** , então a inserção de dados começará a partir de um espaço vazio no slide com o índice especificado.<br/><br/>            Se **false** , então os dados serão adicionados aos slides criados. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_stream | **io.RawIOBase** | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| use_slide_with_index_as_start | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado.<br/><br/>            Se **true** , então a inserção de dados começará a partir de um espaço vazio no slide com o índice especificado.<br/><br/>            Se **false** , então os dados serão adicionados aos slides criados. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_text | **str** | Html a ser adicionado. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for None, todos os objetos externos serão ignorados. |
| uri | **str** | Um URI do HTML especificado. Usado para resolver links relativos. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_stream | **io.RawIOBase** | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for None, todos os objetos externos serão ignorados. |
| uri | **str** | Um URI do HTML especificado. Usado para resolver links relativos. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_text | **str** | Html a ser adicionado. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for None, todos os objetos externos serão ignorados. |
| uri | **str** | Um URI do HTML especificado. Usado para resolver links relativos. |
| use_slide_with_index_as_start | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado.<br/><br/>            Se **true** , então a inserção de dados começará a partir de um espaço vazio no slide com o índice especificado.<br/><br/>            Se **false** , então os dados serão adicionados aos slides criados. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

### Retorno

Slides adicionados.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Posição para inserir. |
| html_stream | **io.RawIOBase** | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver) | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for None, todos os objetos externos serão ignorados. |
| uri | **str** | Um URI do HTML especificado. Usado para resolver links relativos. |
| use_slide_with_index_as_start | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado.<br/><br/>            Se **true** , então a inserção de dados começará a partir de um espaço vazio no slide com o índice especificado.<br/><br/>            Se **false** , então os dados serão adicionados aos slides criados. |



### Veja Também
* classe [`IExternalResourceResolver`](/slides/python-net/pt/aspose.slides.importing/iexternalresourceresolver)
* classe [`SlideCollection`](/slides/python-net/pt/aspose.slides/slidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)