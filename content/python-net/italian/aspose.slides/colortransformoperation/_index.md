---
title: ColorTransformOperation enumeration
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/colortransformoperation/
---
## Enumerazione ColorTransformOperation

Definisce l'operazione di trasformazione del colore.

Il tipo ColorTransformOperation espone i seguenti membri:

## Campi

| Campo | Descrizione |
| :- | :- |
| TINT | Tinta il colore. Il parametro è compreso tra 0 (colore originale) e 1 (bianco). |
| SHADE | Ombreggia il colore. Il parametro è compreso tra 0 (colore originale) e 1 (nero). |
| COMPLEMENT | Cambia il colore in uno complementare RGB.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Cambia il colore in un colore invertito.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Cambia il colore in un grigio con la stessa luminosità. Il parametro è ignorato. |
| SET_ALPHA | Definisce un componente alfa del colore. Il parametro è compreso tra 0 (trasparente) e 1 (opaco). |
| ADD_ALPHA | Aggiunge il valore di un parametro a un componente alfa del colore. Il parametro è compreso tra -1 e 1. |
| MULTIPLY_ALPHA | Moltiplica un componente alfa per il valore di un parametro. |
| SET_HUE | Cambia un componente tonalità del colore al valore di un parametro. Il parametro è compreso tra 0 e 360. |
| ADD_HUE | Aggiunge il valore del parametro al componente tonalità del colore. Il parametro è compreso tra -360 e 360. |
| MULTIPLY_HUE | Moltiplica un componente tonalità per il valore di un parametro. |
| SET_SATURATION | Cambia un componente saturazione del colore al valore di un parametro. Il parametro è compreso tra 0 e 1. |
| ADD_SATURATION | Aggiunge il valore di un parametro a un componente saturazione del colore. Il parametro è compreso tra -1 e 1. |
| MULTIPLY_SATURATION | Moltiplica un componente saturazione per il valore di un parametro. |
| SET_LUMINANCE | Cambia un componente luminanza del colore al valore di un parametro. Il parametro è compreso tra 0 e 1. |
| ADD_LUMINANCE | Aggiunge il valore di un parametro a un componente luminanza del colore. Il parametro è compreso tra -1 e 1. |
| MULTIPLY_LUMINANCE | Moltiplica un componente luminanza per il valore di un parametro. |
| SET_RED | Cambia un componente rosso del colore al valore di un parametro. Il parametro è compreso tra 0 e 1. |
| ADD_RED | Aggiunge il valore di un parametro a un componente rosso del colore. Il parametro è compreso tra -1 e 1. |
| MULTIPLY_RED | Moltiplica un componente rosso per un parametro. |
| SET_GREEN | Cambia un componente verde del colore al valore valore di un parametro. Il parametro è compreso tra 0 e 1. |
| ADD_GREEN | Aggiunge un parametro a un componente verde del colore. Il parametro è compreso tra -1 e 1. |
| MULTIPLY_GREEN | Moltiplica un componente verde del colore per il valore di un parametro. |
| SET_BLUE | Cambia un componente blu del colore al valore di un parametro. Il parametro è compreso tra 0 e 360. |
| ADD_BLUE | Aggiunge il valore di un parametro a un componente blu del colore. Il parametro è compreso tra -1 e 1. |
| MULTIPLY_BLUE | Moltiplica un componente blu per il valore di un parametro. |
| GAMMA | Correzione gamma. Il parametro è ignorato. |
| INVERSE_GAMMA | Correzione gamma inversa. Il parametro è ignorato. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)