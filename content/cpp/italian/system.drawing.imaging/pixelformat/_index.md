---
title: PixelFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica il formato dei dati di colore di un pixel.
type: docs
weight: 326
url: /it/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Specifica il formato dei dati di colore di un pixel.

```cpp
enum class PixelFormat
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Indexed | 65536 | Specifica che i dati del pixel contengono valori indicizzati di colore, il che significa che sono un indice ai colori nella tabella dei colori di sistema. |
| Gdi | 131072 | Specifica che i dati del pixel contengono colori GDI. |
| Alpha | 262144 | Specifica che i dati del pixel contengono valori alfa che non sono pre-moltiplicati. |
| PAlpha | 524288 | Specifica che i dati del pixel contengono valori alfa pre-moltiplicati. |
| Extended | 1048576 | Riservato. |
| Canonical | 2097152 | Specifica il formato del pixel di 32 bit per pixel con profondità colore a 24 bit e un canale alfa a 8 bit. |
| Undefined | 0 | Specifica che il formato del pixel è indefinito. |
| DontCare | 0 | Il formato del pixel non è specificato. |
| Format1bppIndexed | n/a | Specifica che il formato del pixel è a 1 bit per pixel a colori indicizzati. |
| Format4bppIndexed | n/a | Specifica che il formato del pixel è a 4 bit per pixel a colori indicizzati. |
| Format8bppIndexed | n/a | Specifica che il formato del pixel è a 8 bit per pixel a colori indicizzati. |
| Format16bppGrayScale | n/a | Specifica che il formato del pixel è a 16 bit per pixel. L'informazione di colore specifica 65536 tonalità di grigio. |
| Format16bppRgb555 | n/a | Specifica che il formato del pixel è a 16 bit per pixel con 5 bit per ciascuna delle componenti rosso, verde e blu e il bit rimanente non è usato. |
| Format16bppRgb565 | n/a | Specifica che il formato del pixel è a 16 bit per pixel con 5 bit per il rosso, 6 bit per il verde e 5 bit per le componenti blu. |
| Format16bppArgb1555 | n/a | Specifica che il formato del pixel è a 16 bit per pixel con 5 bit per ciascuna delle componenti rosso, verde e blu e 1 bit per l'alfa. |
| Format24bppRgb | n/a | Specifica che il formato del pixel è a 24 bit per pixel con 8 bit per ciascuna delle componenti rosso, verde e blu. |
| Format32bppRgb | n/a | Specifica che il formato del pixel è a 32 bit per pixel con 8 bit per ciascuna delle componenti rosso, verde e blu e gli altri 8 bit non sono usati. |
| Format32bppArgb | n/a | Specifica che il formato del pixel è a 32 bit per pixel con 8 bit per ciascuna delle componenti rosso, verde e blu e 8 bit per l'alfa. |
| Format32bppPArgb | n/a | Specifica che il formato del pixel è a 32 bit per pixel con 8 bit per ciascuna delle componenti rosso, verde e blu e 8 bit per l'alfa. Le componenti rosso, verde e blu sono pre-moltiplicate in base al valore della componente alfa. |
| Format48bppRgb | n/a | Specifica che il formato del pixel è a 48 bit per pixel con 16 bit per ciascuna delle componenti rosso, verde e blu. |
| Format64bppArgb | n/a | Specifica che il formato del pixel è a 64 bit per pixel con 16 bit per ciascuna delle componenti rosso, verde e blu e 16 bit per l'alfa. |
| Format64bppPArgb | n/a | Specifica che il formato del pixel è a 64 bit per pixel con 16 bit per ciascuna delle componenti rosso, verde e blu e 16 bit per l'alfa. Le componenti rosso, verde e blu sono pre-moltiplicate in base al valore della componente alfa. |
| Format32bppCMYK | n/a | Specifica che il formato del pixel è a 32 bit per pixel con 8 bit per ciascuna delle componenti ciano, magenta, giallo e chiave. |
| Max | 16 | Il valore massimo di questo enum. |

## Vedi anche

* Spazio dei nomi [System::Drawing::Imaging](../)
* Libreria [Aspose.Slides](../../)