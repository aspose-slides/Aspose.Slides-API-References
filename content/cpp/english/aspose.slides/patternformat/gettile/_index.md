---
title: GetTile()
second_title: Aspose.Slides for C++ API Reference
description: Creates a tile image for the pattern fill with a specified colors.
type: docs
weight: 66
url: /aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method


Creates a tile image for the pattern fill with a specified colors.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | The background [System::Drawing::Color](../../../system.drawing/color/) for the pattern. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | The foreground [System::Drawing::Color](../../../system.drawing/color/) for the pattern. |

### Return Value

Tile [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) method


Creates a tile image for the pattern fill.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | The default [System::Drawing::Color](../../../system.drawing/color/) |

### Return Value

Tile [IImage](../../iimage/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Color](../../../system.drawing/color/)
* Class [PatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)