---
title: AddBlurEffect()
second_title: Aspose.Slides for C++ API Reference
description: Adds the new Blur effect to the end of a collection.
type: docs
weight: 157
url: /aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) method


Adds the new [Blur](../../blur/) effect to the end of a collection.

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| radius | **double** | The radius of blur. |
| grow | **bool** | Specifies whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. |

### Return Value

Index of the new image effect in a collection.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBlur](../../iblur/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)