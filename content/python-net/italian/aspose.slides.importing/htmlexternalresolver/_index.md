---
title: HtmlExternalResolver class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver classe

Oggetto di callback usato dalla routine di importazione HTML per ottenere oggetti referenziati come immagini.  
L'uso di questo resolver potrebbe creare una vulnerabilità quando un file HTML fornito dal client fa sì che il software server ottenga un file locale o di rete. Usare con cautela. È consigliato non specificare HtmlExternalResolver affatto (verranno letti solo gli oggetti incorporati) oppure creare una sottoclasse che verifichi se l'uri specificato è valido.

Il tipo HtmlExternalResolver espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/it/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Risolve l'URI assoluta a partire dagli URI base e relativi. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/it/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Mappa un URI a un oggetto contenente la risorsa effettiva. |


### Vedi anche
* modulo [`aspose.slides.importing`](/slides/python-net/it/aspose.slides.importing)
* libreria [`Aspose.Slides`](/slides/python-net)