---
title: LockBits()
second_title: Riferimento API di Aspose.Slides per C++
description: Blocca un Bitmap nella memoria di sistema.
type: docs
weight: 118
url: /it/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) metodo

Blocca un [Bitmap](../) nella memoria di sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rettangolo che specifica l'area dell'immagine da bloccare |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specifica il livello di accesso al bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Il formato dei dati di questo bitmap |

### Valore di ritorno

Un puntatore condiviso a un oggetto BitmapData che contiene informazioni sull'operazione di blocco eseguita

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) metodo

Blocca un [Bitmap](../) nella memoria di sistema.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rettangolo che specifica l'area dell'immagine da bloccare |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Specifica il livello di accesso al bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Il formato dei dati di questo bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Contiene informazioni sull'operazione di blocco |

### Valore di ritorno

Un puntatore condiviso a un oggetto BitmapData che contiene informazioni sull'operazione di blocco eseguita

## Vedi anche

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Classe [Rectangle](../../rectangle/)
* Classe [Bitmap](../)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)