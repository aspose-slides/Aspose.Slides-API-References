---
title: add_from_html method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

### Restituisce

Diapositive aggiunte



```python
def add_from_html(self, html_text):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| html_text | **str** | Html da aggiungere. |


## add_from_html(self, html_stream) {#iorawiobase}
Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

### Restituisce

Diapositive aggiunte



```python
def add_from_html(self, html_stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Un oggetto Stream che sarà usato come sorgente di un file HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

### Restituisce

Diapositive aggiunte.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| html_text | **str** | Html da aggiungere. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è None tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta.

### Restituisce

Diapositive aggiunte.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Un oggetto Stream che sarà usato come sorgente di un file HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è None tutti gli oggetti esterni saranno ignorati. |
| uri | **str** | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |



### Vedi anche
* classe [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver)
* classe [`ISlideCollection`](/slides/python-net/it/aspose.slides/islidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)