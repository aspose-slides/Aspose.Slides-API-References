---
title: GetTileImage()
second_title: Aspose.Slides for C++ API Reference
description: Creates a tile image for the pattern fill with a specified colors.
type: docs
weight: 40
url: /aspose.slides/ipatternformateffectivedata/gettileimage/
---
## IPatternFormatEffectiveData::GetTileImage(System::Drawing::Color, System::Drawing::Color) method


Creates a tile image for the pattern fill with a specified colors.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::IPatternFormatEffectiveData::GetTileImage(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | The background [System::Drawing::Color](../../../system.drawing/color/) for the pattern. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | The foreground [System::Drawing::Color](../../../system.drawing/color/) for the pattern. |

### Return Value

Tile [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

Deprecated
:   Use GetTileIImage(SlidesImage image) method instead. The method will be removed after release of version 24.7.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Color](../../../system.drawing/color/)
* Class [IPatternFormatEffectiveData](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)