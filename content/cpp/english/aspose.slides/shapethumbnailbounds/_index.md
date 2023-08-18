---
title: ShapeThumbnailBounds
second_title: Aspose.Slides for C++ API Reference
description: Enumeration of types of shape thumbnail bounds.
type: docs
weight: 6033
url: /aspose.slides/shapethumbnailbounds/
---
## ShapeThumbnailBounds enum


Enumeration of types of shape thumbnail bounds.

```cpp
enum class ShapeThumbnailBounds
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Slide | 0 | [Shape](../shape/) thumbnail will have the size equal to slide size. [Shape](../shape/) position will be saved. |
| Shape | 1 | [Shape](../shape/) thumbnail will have size equal to the shape bounds rectangle with taking into account shape outline settings. |
| Appearance | 2 | [Shape](../shape/) thumbnail will have size equal to the shape appearance (in bounds of a slide). It can be cases when shape appearance doesn't fit into the shape bounds. E.g. rotation, miter join of acute angle , 3D effects, etc. |

## See Also

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)