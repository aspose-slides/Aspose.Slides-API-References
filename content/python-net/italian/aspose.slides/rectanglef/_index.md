---
title: RectangleF class
second_title: Aspose.Slides per Python via .NET API Reference
description: Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
url: /it/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF classe

Memorizza un insieme di quattro numeri a virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo. Compatibile con .NET `System.Drawing.RectangleF`.

**Ereditarietà:**[`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/it/aspose.slides/rectangle)

Il tipo RectangleF espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/it/aspose.slides/rectanglef/__init__/#float-float-float-float) | Crea un rettangolo con la posizione e le dimensioni specificate. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`x`](/slides/python-net/it/aspose.slides/rectanglef/x/) | Restituisce la coordinata x dell'angolo superiore sinistro di questo rettangolo.<br/>            Solo lettura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/rectanglef/y/) | Restituisce la coordinata y dell'angolo superiore sinistro di questo rettangolo.<br/>            Solo lettura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/rectanglef/width/) | Restituisce la larghezza di questo rettangolo.<br/>            Solo lettura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/rectanglef/height/) | Restituisce l'altezza di questo rettangolo.<br/>            Solo lettura **float**. |
| [`left`](/slides/python-net/it/aspose.slides/rectanglef/left/) | Restituisce la coordinata x del margine sinistro di questo rettangolo. È uguale a `x`.<br/>            Solo lettura **float**. |
| [`top`](/slides/python-net/it/aspose.slides/rectanglef/top/) | Restituisce la coordinata y del margine superiore di questo rettangolo. È uguale a `y`.<br/>            Solo lettura **float**. |
| [`right`](/slides/python-net/it/aspose.slides/rectanglef/right/) | Restituisce la coordinata x che è la somma di `x` e `width` di questo rettangolo.<br/>            Solo lettura **float**. |
| [`bottom`](/slides/python-net/it/aspose.slides/rectanglef/bottom/) | Restituisce la coordinata y che è la somma di `y` e `height` di questo rettangolo.<br/>            Solo lettura **float**. |
| [`is_empty`](/slides/python-net/it/aspose.slides/rectanglef/is_empty/) | Specifica se tutte le proprietà numeriche di questo rettangolo hanno valore zero.<br/>            Solo lettura **bool**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/it/aspose.slides/rectanglef/contains/#float-float) | Determina se il punto specificato è contenuto all'interno di questo rettangolo. |
| [`contains(self, point)`](/slides/python-net/it/aspose.slides/rectanglef/contains/#pointf) | Determina se il punto specificato è contenuto all'interno di questo rettangolo. |
| [`contains(self, rect)`](/slides/python-net/it/aspose.slides/rectanglef/contains/#rectanglef) | Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questo rettangolo. |


### Osservazioni

I rettangoli sono confrontati per posizione e dimensione con `==` e possono essere usati come chiavi di dizionario o membri di un insieme.


### Vedi anche
* classe [`Rectangle`](/slides/python-net/it/aspose.slides/rectangle)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)