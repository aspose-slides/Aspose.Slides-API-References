---
title: insert_from_html method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | HTML da aggiungere. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà utilizzato come origine di un file HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | HTML da aggiungere. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , allora l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato.<br/><br/>            Se **false** , allora i dati verranno aggiunti alle diapositive create. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà utilizzato come origine di un file HTML. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , allora l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato.<br/><br/>            Se **false** , allora i dati verranno aggiunti alle diapositive create. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | HTML da aggiungere. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None, tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà utilizzato come origine di un file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None, tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_text | **str** | HTML da aggiungere. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None, tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , allora l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato.<br/><br/>            Se **false** , allora i dati verranno aggiunti alle diapositive create. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata.

### Restituisce

Diapositive aggiunte.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Posizione in cui inserire. |
| html_stream | **io.RawIOBase** | Un oggetto Stream che verrà utilizzato come origine di un file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto callback usato per recuperare oggetti esterni. Se questo parametro è None, tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| use_slide_with_index_as_start | **bool** | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato.<br/><br/>            Se **true** , allora l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato.<br/><br/>            Se **false** , allora i dati verranno aggiunti alle diapositive create. |



### Vedi anche
* classe [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver)
* classe [`SlideCollection`](/slides/python-net/it/aspose.slides/slidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)