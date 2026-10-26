---
title: Clone()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una copia dell'oggetto corrente.
type: docs
weight: 183
url: /it/system.drawing/bitmap/clone/
---
## Bitmap::Clone() metodo

Crea una copia dell'oggetto corrente.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Valore di ritorno

Una copia dell'oggetto corrente.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) metodo

Crea un oggetto [Bitmap](../) che rappresenta una copia di una regione dell'immagine bitmap rappresentata dall'oggetto corrente.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Il rettangolo che specifica la regione da copiare |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Il formato pixel per il nuovo [Bitmap](../) |

### Valore di ritorno

L'oggetto [Bitmap](../) creato

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) metodo

Crea un oggetto [Bitmap](../) che rappresenta una copia di una regione dell'immagine bitmap rappresentata dall'oggetto corrente.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Il rettangolo che specifica la regione da copiare |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Il formato pixel per il nuovo [Bitmap](../) |

### Valore di ritorno

L'oggetto [Bitmap](../) creato

## Vedi anche

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)