---
title: Rectangle class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo.
type: docs
url: /it/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle classe

Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo. Compatibile con .NET `System.Drawing.Rectangle`.

Il tipo Rectangle espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/it/aspose.slides/rectangle/__init__/#int-int-int-int) | Crea un rettangolo con la posizione e le dimensioni specificate. I valori float vengono troncati a interi. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`x`](/slides/python-net/it/aspose.slides/rectangle/x/) | Restituisce la coordinata x dell'angolo superiore sinistro di questo rettangolo.<br/>            Solo lettura **int**. |
| [`y`](/slides/python-net/it/aspose.slides/rectangle/y/) | Restituisce la coordinata y dell'angolo superiore sinistro di questo rettangolo.<br/>            Solo lettura **int**. |
| [`width`](/slides/python-net/it/aspose.slides/rectangle/width/) | Restituisce la larghezza di questo rettangolo.<br/>            Solo lettura **int**. |
| [`height`](/slides/python-net/it/aspose.slides/rectangle/height/) | Restituisce l'altezza di questo rettangolo.<br/>            Solo lettura **int**. |
| [`left`](/slides/python-net/it/aspose.slides/rectangle/left/) | Restituisce la coordinata x del lato sinistro di questo rettangolo. Uguale a `x`.<br/>            Solo lettura **int**. |
| [`top`](/slides/python-net/it/aspose.slides/rectangle/top/) | Restituisce la coordinata y del bordo superiore di questo rettangolo. Uguale a `y`.<br/>            Solo lettura **int**. |
| [`right`](/slides/python-net/it/aspose.slides/rectangle/right/) | Restituisce la coordinata x che è la somma di `x` e `width` di questo rettangolo.<br/>            Solo lettura **int**. |
| [`bottom`](/slides/python-net/it/aspose.slides/rectangle/bottom/) | Restituisce la coordinata y che è la somma di `y` e `height` di questo rettangolo.<br/>            Solo lettura **int**. |
| [`is_empty`](/slides/python-net/it/aspose.slides/rectangle/is_empty/) | Specifica se tutte le proprietà numeriche di questo rettangolo hanno valore zero.<br/>            Solo lettura **bool**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/it/aspose.slides/rectangle/contains/#int-int) | Determina se il punto specificato è contenuto all'interno di questo rettangolo. |
| [`contains(self, point)`](/slides/python-net/it/aspose.slides/rectangle/contains/#point) | Determina se il punto specificato è contenuto all'interno di questo rettangolo. |
| [`contains(self, rect)`](/slides/python-net/it/aspose.slides/rectangle/contains/#rectangle) | Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questo rettangolo. |

### Osservazioni

I rettangoli vengono confrontati per posizione e dimensione con `==` e possono essere usati come chiavi di dizionario o membri di un set.

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)