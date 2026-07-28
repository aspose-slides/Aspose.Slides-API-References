---
title: Clone()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy kopię bieżącego obiektu.
type: docs
weight: 183
url: /pl/system.drawing/bitmap/clone/
---
## Bitmap::Clone() method

Tworzy kopię bieżącego obiektu.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Return Value

Kopia bieżącego obiektu.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) method

Tworzy obiekt [Bitmap](../), który reprezentuje kopię regionu obrazu bitmapy reprezentowanego przez bieżący obiekt.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Prostokąt określający region do skopiowania |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format pikseli nowego [Bitmap](../) |

### Return Value

Utworzony obiekt [Bitmap](../)

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) method

Tworzy obiekt [Bitmap](../), który reprezentuje kopię regionu obrazu bitmapy reprezentowanego przez bieżący obiekt.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Prostokąt określający region do skopiowania |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format pikseli nowego [Bitmap](../) |

### Return Value

Utworzony obiekt [Bitmap](../)

## See Also

* Wyliczenie [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Image](../../image/)
* Klasa [Bitmap](../)
* Klasa [Rectangle](../../rectangle/)
* Klasa [RectangleF](../../rectanglef/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)