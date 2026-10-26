---
title: ColorTransformOperation
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce l'operazione di trasformazione del colore.
type: docs
weight: 5747
url: /it/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

Definisce l'operazione di trasformazione del colore.

```cpp
enum class ColorTransformOperation
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Tint | 0 | Applica una tinta al colore. Il parametro è compreso tra 0 (colore originale) e 1 (bianco). |
| Shade | 1 | Scurisce il colore. Il parametro è compreso tra 0 (colore originale) e 1 (nero). |
| Complement | 2 | Cambia il colore in uno complementare RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | Cambia il colore in un colore invertito. r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | Cambia il colore in una tonalità di grigio con la stessa luminosità. Il parametro viene ignorato. |
| SetAlpha | 5 | Definisce una componente alfa del colore. Il parametro è compreso tra 0 (trasparente) e 1 (opaco). |
| AddAlpha | 6 | Aggiunge il valore del parametro a una componente alfa del colore. Il parametro è compreso tra -1 e 1. |
| MultiplyAlpha | 7 | Moltiplica una componente alfa per il valore del parametro. |
| SetHue | 8 | Cambia la componente tonalità del colore al valore del parametro. Il parametro è compreso tra 0 e 360. |
| AddHue | 9 | Aggiunge il valore del parametro alla componente tonalità del colore. Il parametro è compreso tra -360 e 360. |
| MultiplyHue | 10 | Moltiplica una componente tonalità per il valore del parametro. |
| SetSaturation | 11 | Cambia la componente saturazione del colore al valore del parametro. Il parametro è compreso tra 0 e 1. |
| AddSaturation | 12 | Aggiunge il valore del parametro a una componente saturazione del colore. Il parametro è compreso tra -1 e 1. |
| MultiplySaturation | 13 | Moltiplica una componente saturazione per il valore del parametro. |
| SetLuminance | 14 | Cambia la componente luminanza del colore al valore del parametro. Il parametro è compreso tra 0 e 1. |
| AddLuminance | 15 | Aggiunge il valore del parametro a una componente luminanza del colore. Il parametro è compreso tra -1 e 1. |
| MultiplyLuminance | 16 | Moltiplica una componente luminanza per il valore del parametro. |
| SetRed | 17 | Cambia la componente rossa del colore al valore del parametro. Il parametro è compreso tra 0 e 1. |
| AddRed | 18 | Aggiunge il valore del parametro a una componente rossa del colore. Il parametro è compreso tra -1 e 1. |
| MultiplyRed | 19 | Moltiplica una componente rossa per un parametro. |
| SetGreen | 20 | Cambia la componente verde del colore al valore del parametro. Il parametro è compreso tra 0 e 1. |
| AddGreen | 21 | Aggiunge un parametro a una componente verde del colore. Il parametro è compreso tra -1 e 1. |
| MultiplyGreen | 22 | Moltiplica una componente verde del colore per il valore del parametro. |
| SetBlue | 23 | Cambia la componente blu del colore al valore del parametro. Il parametro è compreso tra 0 e 360. |
| AddBlue | 24 | Aggiunge il valore del parametro a una componente blu del colore. Il parametro è compreso tra -1 e 1. |
| MultiplyBlue | 25 | Moltiplica una componente blu del colore per il valore del parametro. |
| Gamma | 26 | Correzione gamma. Il parametro viene ignorato. |
| InverseGamma | 27 | Correzione gamma inversa. Il parametro viene ignorato. |

## Vedi anche

* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)