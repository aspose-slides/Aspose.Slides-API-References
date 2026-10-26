---
title: insert_from_html method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | Html da aggiungere. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà usato come sorgente di un file HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | Html da aggiungere. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            If **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            If **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | Html da aggiungere. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | Html da aggiungere. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            If **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            If **false** , then data will be added to the created slides. |



### Vedi anche
* classe [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver)
* classe [`ISlideCollection`](/slides/python-net/it/aspose.slides/islidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)