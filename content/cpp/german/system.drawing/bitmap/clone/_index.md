---
title: Clone()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine Kopie des aktuellen Objekts.
type: docs
weight: 183
url: /de/system.drawing/bitmap/clone/
---
## Bitmap::Clone() Methode

Erstellt eine Kopie des aktuellen Objekts.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Rückgabewert

Eine Kopie des aktuellen Objekts.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) Methode

Erstellt ein [Bitmap](../) Objekt, das eine Kopie eines Bereichs des Bitmap-Bildes darstellt, das durch das aktuelle Objekt repräsentiert wird.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Das Rechteck, das den zu kopierenden Bereich angibt |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Das Pixel-Format für das neue [Bitmap](../) |

### Rückgabewert

Das erstellte [Bitmap](../) Objekt

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) Methode

Erstellt ein [Bitmap](../) Objekt, das eine Kopie eines Bereichs des Bitmap-Bildes darstellt, das durch das aktuelle Objekt repräsentiert wird.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Das Rechteck, das den zu kopierenden Bereich angibt |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Das Pixel-Format für das neue [Bitmap](../) |

### Rückgabewert

Das erstellte [Bitmap](../) Objekt

## Siehe auch

* Aufzählung [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../../image/)
* Klasse [Bitmap](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)