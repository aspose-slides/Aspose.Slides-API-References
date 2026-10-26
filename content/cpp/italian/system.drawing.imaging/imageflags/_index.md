---
title: ImageFlags
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta gli attributi dei dati pixel rappresentati da un oggetto Image.
type: docs
weight: 274
url: /it/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Rappresenta gli attributi dei dati pixel rappresentati da un oggetto [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Scalabile. |
| HasAlpha | 2 | Contiene informazioni alpha. |
| HasTranslucent | 4 | Ci sono valori alpha maggiori di 0 e minori di 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | I dati pixel sono rappresentati nello spazio colore RGB. |
| ColorSpaceCmyk | 32 | I dati pixel sono rappresentati nello spazio colore CMYK. |
| ColorSpaceGray | 64 | I dati pixel sono in scala di grigi. |
| ColorSpaceYcbcr | 128 | I dati pixel sono rappresentati nello spazio colore YCBCR. |
| ColorSpaceYcck | 256 | I dati pixel sono rappresentati nello spazio colore YCCK. |
| HasRealDpi | 4096 | Le informazioni DPI sono memorizzate nell'immagine. |
| HasRealPixelSize | 8192 | La dimensione di un pixel è memorizzata nell'immagine. |
| ReadOnly | 65536 | I dati pixel sono a sola lettura. |
| Caching | 131072 | Può essere memorizzato nella cache per un accesso più veloce. |

## Vedi anche

* Spazio dei nomi [System::Drawing::Imaging](../)
* Libreria [Aspose.Slides](../../)