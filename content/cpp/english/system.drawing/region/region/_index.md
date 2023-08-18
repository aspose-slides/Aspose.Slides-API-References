---
title: Region()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of Region class.
type: docs
weight: 1
url: /system.drawing/region/region/
---
## Region::Region() constructor


Constructs a new instance of [Region](../) class.

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) constructor


Constructs a new instance of [Region](../) class that represents a region defined by the specified rectangle.

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | A rectangle that defines the region |

## Region::Region(const Rectangle\&) constructor


Constructs a new instance of [Region](../) class that represents a region defined by the specified rectangle.

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | A rectangle that defines the region |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) constructor


Constructs a new instance of [Region](../) class that represents a region defined by the specified path.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | A path that defines the region |

## Region::Region(const SkPath\&) constructor




```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) constructor


Constructs a new instance of [Region](../) class that represents a region defined by the specified RegionData object.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | A RegionData object that defines the region |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Class [RegionData](../../../system.drawing.drawing2d/regiondata/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)