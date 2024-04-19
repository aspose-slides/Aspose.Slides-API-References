---
title: GetTileImage()
second_title: Aspose.Slides for C++ API Reference
description: Creates a tile image for the pattern fill with a specified colors.
type: docs
weight: 53
url: /aspose.slides/patternformat/gettileimage/
---
## PatternFormat::GetTileImage(System::Drawing::Color, System::Drawing::Color) method


Creates a tile image for the pattern fill with a specified colors.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::PatternFormat::GetTileImage(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | The background [System::Drawing::Color](../../../system.drawing/color/) for the pattern. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | The foreground [System::Drawing::Color](../../../system.drawing/color/) for the pattern. |

### Return Value

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

Deprecated
:   Use GetTile(Color background, Color foreground) method instead. The method will be removed after release of version 24.7.

## PatternFormat::GetTileImage(System::Drawing::Color) method


Creates a tile image for the pattern fill.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::PatternFormat::GetTileImage(System::Drawing::Color styleColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | The default [System::Drawing::Color](../../../system.drawing/color/), defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

### Return Value

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

Deprecated
:   Use GetTile(Color styleColor) method instead. The method will be removed after release of version 24.7.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Color](../../../system.drawing/color/)
* Class [PatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)