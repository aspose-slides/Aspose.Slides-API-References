---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API Reference
description: Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read float.
type: docs
weight: 300
url: /aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() method


Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Remarks


Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. In addition to this, the text body itself has a rotation of -90 degrees counter-clockwise applied to it. Then the resulting shape would appear to be rotated but the text within it would appear as though it had not been rotated at all. 
## See Also

* Class [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)