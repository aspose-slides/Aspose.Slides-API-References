---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API Reference
description: Adds the new Bi-Level (black/white) effect to the end of a collection.
type: docs
weight: 144
url: /aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) method


Adds the new Bi-Level (black/white) effect to the end of a collection.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
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
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)