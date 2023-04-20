---
title: GetHeight()
second_title: Aspose.Slides for C++ API Reference
description: Returns the line spacing of the font represented by the current object, in the current unit of a specified Graphics object.
type: docs
weight: 14
url: /cpp/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) method


Returns the line spacing of the font represented by the current object, in the current unit of a specified [Graphics](../../graphics/) object.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | A [Graphics](../../graphics/) object that specifies the measurement units |

## Font::GetHeight(float) method


Returns the height of the font represented by the current object when drawn to a display device with the specified vertical resolution.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dpi | **float** | The vertical resolution of the display device |

### Return Value

The hegiht of the font in pixels

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../../graphics/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)