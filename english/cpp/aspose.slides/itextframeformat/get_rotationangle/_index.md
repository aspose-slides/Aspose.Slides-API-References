---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read float.
type: docs
weight: 339
url: /cpp/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() method


Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Remarks


Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. In addition to this, the text body itself has a rotation of -90 degrees counter-clockwise applied to it. Then the resulting shape would appear to be rotated but the text within it would appear as though it had not been rotated at all. 
## See Also

* Class [ITextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
