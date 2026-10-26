---
title: add_from_html method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Aggiunge testo dalla stringa HTML specificata alla collezione.


```python
def add_from_html(self, text):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | **str** | Testo HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Aggiunge testo dalla stringa HTML specificata alla collezione.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | **str** | Testo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver) | Oggetto callback del resolver che risolve gli URI e recupera gli oggetti referenziati. |
| uri | **str** | URI per aggiungere il documento HTML. Usato per risolvere i collegamenti relativi. |

### Osservazioni

Specificare resolver può potenzialmente introdurre una vulnerabilità. Usare con cautela.



### Vedi anche
* classe [`IExternalResourceResolver`](/slides/python-net/it/aspose.slides.importing/iexternalresourceresolver)
* classe [`ParagraphCollection`](/slides/python-net/it/aspose.slides/paragraphcollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)