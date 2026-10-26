---
title: ExternalResourceResolver class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver classe

Classe di callback utilizzata per risolvere risorse esterne durante l'importazione di documenti Html, Svg.
            L'utilizzo di questo risolutore potrebbe creare una vulnerabilità quando un file HTML o SVG fornito dal client farà sì che il software del server ottenga un file locale o di rete. Usare con cautela. Si raccomanda di non specificare ExternalResourceResolver affatto (verranno letti solo gli oggetti incorporati) o di creare una sottoclasse che verifichi se l'uri specificato è valido.

Il tipo ExternalResourceResolver espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/it/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Risolve l'URI assoluto a partire dall'URI base e da quello relativo. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/it/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Mappa un'URI a un oggetto che contiene la risorsa effettiva. |


### Vedi anche
* modulo [`aspose.slides.importing`](/slides/python-net/it/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)