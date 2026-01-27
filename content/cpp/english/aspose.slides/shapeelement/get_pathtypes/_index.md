---
title: get_PathTypes()
second_title: Aspose.Slides for C++ API Reference
description: Gets an array of byte values that specify the type of each point in the element's path.
type: docs
weight: 27
url: /aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() method


Gets an array of byte values that specify the type of each point in the element's path.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Remarks


**0** Indicates that the point is the start of a figure.

**1** Indicates that the point is one of the two endpoints of a line.

**3** Indicates that the point is an endpoint or control point of a cubic Bezier spline.

**7** Masks all bits except for the three low-order bits, which indicate the point type.

**16** Specifies that the corresponding segment is dashed.

**32** Specifies that the point is a marker.

**128** Specifies that the point is the last point in a closed subpath (figure).

**129** Indicates a data point that is both a line segment endpoint and the last point of a closed subpath.
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ShapeElement](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)