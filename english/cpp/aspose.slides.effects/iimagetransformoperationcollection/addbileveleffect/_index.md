---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API Reference
description: Adds the new Bi-Level (black/white) effect to the end of a collection.
type: docs
weight: 118
url: /cpp/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(**float**) method


Adds the new Bi-Level (black/white) effect to the end of a collection.

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | **float** | the luminance threshold for the Bi-Level effect. Values greater than or equal to the threshold are set to white. Values lesser than the threshold are set to black. |

### Return Value

Index of the new image effect in a collection.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBiLevel](../../ibilevel/)
* Class [IImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)
