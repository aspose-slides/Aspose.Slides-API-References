---
title: add_from_html method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Aggiunge testo da una stringa HTML specificata alla raccolta.


```python
def add_from_html(self, text):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | **str** | Testo HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Aggiunge testo da una stringa HTML specificata alla raccolta.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | **str** | Testo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Oggetto callback del risolutore che risolve gli URI e recupera gli oggetti referenziati. |
| uri | **str** | URI per aggiungere il documento HTML. Usato per risolvere i collegamenti relativi. |

### Osservazioni

Specificare il risolutore può potenzialmente introdurre una vulnerabilità. Usare con cautela.



### Vedi anche
* classe [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver)
* classe [`IParagraphCollection`](/slides/python-net/it/aspose.slides/iparagraphcollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)